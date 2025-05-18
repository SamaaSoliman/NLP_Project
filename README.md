## *NOTE*
*Each project milestone includes a detailed report (PDF) in its respective directory that documents the methodology, implementation details, and results. Please refer to these reports for comprehensive information about each phase of the project.*

## Project Milestones:

### Milestone 1: Data Preprocessing and Analysis
- Cleaned and preprocessed "الدحيح" YouTube channel scripts and metadata
- Performed text normalization for Arabic text including diacritic removal
- Implemented custom stopword removal for Arabic language
- Conducted exploratory data analysis on episode popularity metrics
- Analyzed text statistics including word frequencies and TF-IDF 
- Created visualizations to understand content distribution and features

### Milestone 2: Question Answering Model Development
- Implemented various neural network architectures for question answering
- Trained models on the SQuAD dataset for transferable knowledge
- Created encoder-decoder architectures with attention mechanisms
- Experimented with different model configurations (LSTM, Transformer)
- Evaluated models using accuracy and other relevant metrics
- Generated visualizations to track model performance across training epochs

### Milestone 3: Question Answering with RAG (Zero-shot vs. COT)
- Implemented Retrieval-Augmented Generation (RAG) techniques
- Developed document retrieval system for contextual question answering
- Integrated memory capabilities for multi-turn conversations
- Evaluated system performance using ROUGE metrics
- Implemented two distinct prompting approaches:
    - Zero-shot prompting: Direct question answering based on retrieved context
    - Chain of Thought (CoT) prompting: Step-by-step reasoning before providing the answer