# Job Descriptions 2025 — NLP Study on Tech and Non-Tech Roles

This repository contains an in-depth Natural Language Processing (NLP) analysis of the dataset 
**[Job Descriptions 2025: Tech and Non-Tech Roles](https://www.kaggle.com/datasets/adityarajsrv/job-descriptions-2025-tech-and-non-tech-roles)**,
focusing on trends, semantics, and skill requirements across technical and non-technical positions.

---

## Dataset Information

**Source:** Kaggle — [Job Descriptions 2025: Tech and Non-Tech Roles](https://www.kaggle.com/datasets/adityarajsrv/job-descriptions-2025-tech-and-non-tech-roles)  
**Author:** Aditya Raj  
**License:** Dataset made available under [CC BY-SA 4.0 License](https://creativecommons.org/licenses/by-sa/4.0/)

If you use this dataset, please cite as:

> Raj, Aditya. *Job Descriptions 2025: Tech and Non-Tech Roles*. Kaggle, 2025.  
> [https://www.kaggle.com/datasets/adityarajsrv/job-descriptions-2025-tech-and-non-tech-roles](https://www.kaggle.com/datasets/adityarajsrv/job-descriptions-2025-tech-and-non-tech-roles)

---

## 🎯 Project Objective

To apply **NLP techniques** to explore, classify, and extract insights from modern job descriptions — 
analyzing **semantic similarities, emerging skill clusters, and language differences** between tech and non-tech roles.

We will:
- Clean and normalize text data.
- Apply embeddings and topic modeling.
- Detect semantic clusters and latent patterns.
- Compare linguistic and structural differences between categories.

---

## 🧩 Repository Structure

```bash

job_descriptions_nlp_2025/
│
├── data/
│   ├── raw/                   # Original Kaggle CSV files
│   ├── processed/             # Cleaned and preprocessed datasets
│
├── src/
│   ├── 01_exploration.ipynb    # Initial data exploration and structure
│   ├── 02_cleaning.ipynb       # Text normalization and preprocessing
│   ├── 03_eda_language.ipynb   # Exploratory linguistic analysis
│   ├── 04_topic_modeling.ipynb # Topic modeling (LDA / BERTopic)
│   ├── 05_embeddings.ipynb     # Word2Vec / BERT embeddings
│   ├── 06_classification.ipynb # Predicting job type (Tech vs Non-Tech)
│   ├── 07_skills_network.ipynb # Graph of skills co-occurrence
│   ├── 08_sentiment_roles.ipynb # Sentiment & tone analysis
│   ├── 09_trends_2025.ipynb    # Emerging skill/trend analysis
│
├── requirements.txt
├── README.md
└── LICENSE

