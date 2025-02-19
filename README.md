# Hazard Classification Model - European Food Safety Agency (EFSA)

## 📌 Project Overview
This project focuses on the development of a **hazard classification model** for text data related to food recalls. Conducted as part of **SemEval 2025 Task 9**, the model leverages machine learning techniques to classify food safety hazards effectively. 

## 🔍 Key Features
- **Fine-tuned Transformer Models**: Utilized **RoBERTa** to enhance classification accuracy.
- **Random Forest Algorithms**: Implemented traditional machine learning models for baseline comparisons.
- **Data Augmentation with 13 Free LLMs**: Leveraged multiple open-source large language models for dataset expansion.
- **AWS SageMaker Integration**: Deployed models on a scalable cloud infrastructure for efficient training and inference.
- **Fallback Backtranslation**: Enhanced dataset diversity using backtranslation techniques.

## 🛠️ Technologies Used
- **Python (PyTorch, Scikit-Learn)** – Model training and evaluation.
- **AWS SageMaker** – Scalable cloud-based machine learning.
- **Hugging Face Transformers** – Implementation of RoBERTa and other NLP models.
- **NLTK** – Text preprocessing and tokenization.
- **Groq API** – Augmenting data via LLMs.
