 LLM Hallucination Detection

 Overview

This project focuses on detecting hallucinated responses generated
by Large Language Models using Natural Language Processing techniques.

The project is based on the following 2026 research paper:

A Hybrid Framework for Hallucination Detection in Large Language Models**

Dataset

The project uses the HaluEval Dialogue dataset.

The dataset contains dialogue histories along with factual and
hallucinated responses.

Current Progress

- Dataset loading
- Dataset inspection
- Missing-value analysis
- Data preprocessing
- Binary label construction
- Exploratory Data Analysis
- Train/Validation/Test split
- Initial BERT tokenization

Methodology

The planned baseline architecture consists of:

HaluEval Dataset
→ Data Preprocessing
→ BERT / RoBERTa / DeBERTa
→ Contextual Embeddings
→ Deep Learning Classifier
→ Hallucination Detection

Future Work

- Transformer-based feature extraction
- Deep learning classification
- Model comparison
- Evaluation using accuracy, precision, recall and F1-score
- Investigation of enhanced semantic/NLI features
