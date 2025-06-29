📰 News Classification with TF-IDF and Machine Learning
📁 Repository Structure
This repository aims to build a news classification system using TF-IDF vectorization and machine learning classification models. It includes both an exploratory phase and a deployment-ready pipeline.

🔍 Jupyter Notebooks
news_classification.ipynb:
Contains the full exploratory data analysis (EDA), feature engineering, model building, evaluation, and model selection.

This notebook is recommended for understanding the entire development pipeline.

news_classification_deployment.ipynb:
Contains the final optimized and cleaned code, ready for deployment or integration into an application.

This notebook is lightweight and focuses on reproducibility and inference.

📊 Dataset Overview
Source: [Kaggle - News Category Dataset](https://www.kaggle.com/datasets/rmisra/news-category-dataset/data)
Records: ~210,000 news headlines
Timeframe: 2012–2022

📝 Citation Required: Please cite the dataset using the BibTeX provided on the Kaggle dataset page if used in research.

📦 Dataset Columns
Column Name	Description
category	Category under which the article was published
headline	Headline of the news article
authors	List of authors who wrote the article
link	URL to the original news article
short_description	Abstract or summary of the article
date	Date of article publication

🛠️ Tools & Techniques Used
Text Vectorization: TF-IDF

Modeling: Multinomial Naive Bayes, Logistic Regression, etc.

EDA Tools: Matplotlib, Seaborn, WordCloud

Model Evaluation: Accuracy, Precision, Recall, F1 Score

Deployment Ready Format: Cleaned pipeline for prediction use
