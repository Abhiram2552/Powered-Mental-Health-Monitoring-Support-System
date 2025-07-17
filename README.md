Powered Mental Health Monitoring & Support System

Project Overview

This project presents an AI-powered system designed to offer preliminary insights into potential mental health states by analyzing textual data, such as simulated journal entries or social media posts. Leveraging Natural Language Processing (NLP) and Machine Learning, the system aims for early identification of mental health indicators (e.g., stress, anxiety, depression, suicidal ideation).

A foundational aspect of this project is its commitment to Explainable AI (XAI), specifically incorporating LIME (Local Interpretable Model-agnostic Explanations). This ensures transparency by clearly showing why the model makes a particular prediction, thereby fostering user trust and providing actionable insights.

Disclaimer: This tool is developed for academic and demonstrative purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. If you or someone you know is experiencing mental health concerns, please seek help from a qualified healthcare professional.

Features

Text Classification: Categorizes textual input into relevant mental health-related classes (e.g., 'suicide', 'non-suicide' based on the dataset used).

Natural Language Processing (NLP): Utilizes standard NLP techniques for efficient text cleaning, tokenization, and feature extraction.

Machine Learning Model: Employs a robust classification algorithm to predict mental health states.

Explainable AI (LIME): Provides local, interpretable explanations for each prediction, highlighting the specific words or phrases that most influenced the model's decision.

Interactive Web Application (Streamlit): A user-friendly interface for real-time text analysis and explanation. (Deployment status: Coming soon / Deployed via Streamlit Cloud - Choose one that applies)

Why Explainable AI (XAI)?

In sensitive domains like mental health, understanding why an AI model arrives at a particular conclusion is paramount. "Black-box" models, while powerful, often lack the transparency needed for critical applications. By incorporating LIME, this project aims to:

Build Trust: Users can clearly see which parts of their text led to a specific prediction, fostering confidence in the system.

Aid Interpretation: Researchers or practitioners can gain valuable insights into the linguistic patterns the model learns and prioritizes.

Facilitate Debugging: Understanding misclassifications becomes significantly easier by analyzing the contributing factors, aiding in model improvement.

Technical Stack

Language: Python

Core Libraries:

pandas, numpy: Data manipulation and numerical operations.

nltk, re, string: Natural Language Processing (text cleaning, lemmatization, stop words removal).

scikit-learn: Machine Learning (TF-IDF vectorization, Logistic Regression for classification, model selection, evaluation metrics).

lime: Local Interpretable Model-agnostic Explanations (for XAI).

joblib: Model persistence (saving/loading trained models).

streamlit: For building the interactive web application.

Environment: Kaggle Notebooks for development, local environment for Streamlit app.

Version Control: Git & GitHub

Dataset

This project primarily utilizes the "Suicide and Depression Detection" dataset sourced from Kaggle. This dataset typically contains Reddit posts labeled as 'suicide' or 'non-suicide'.

Ethical Note: The dataset consists of publicly available Reddit posts. All data used is anonymized and utilized strictly for academic research and demonstration purposes. Strict disclaimers are in place within the application to prevent misuse or misinterpretation of predictions.
