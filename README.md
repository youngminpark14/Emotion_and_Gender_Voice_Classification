# Emotion_and_Gender_Voice_Classification

Voice Classification by Gender and Emotion
Project Overview
This project implements machine learning classifiers to predict speaker gender and emotion from voice samples using Support Vector Machines (SVM). The analysis includes multiple languages (English, German, Spanish, Russian) and compares accuracy across different prediction scenarios.
Features

Gender Classification: Predicts male/female speaker identity with 96.67% accuracy
Emotion Classification: Identifies 7 emotion categories (anger, fear, happiness, sadness, disgust, neutral, other) with 70% accuracy
Multiclass Prediction: Combined gender and emotion classification
Data Visualization: Principal Component Analysis (PCA) plots and confusion matrices
Model Optimization: Hyperparameter tuning and feature normalization

Datasets

EmoDB: Berlin Database of Emotional Speech (German)
RAVDESS: Ryerson Audio-Visual Database of Emotional Speech and Song
Additional multilingual datasets for broader language coverage

Technical Implementation

Feature Extraction: Mel-Frequency Cepstral Coefficients (MFCCs) using Librosa
Algorithm: Support Vector Machines with linear and RBF kernels
Preprocessing: StandardScaler normalization
Optimization: GridSearchCV for hyperparameter tuning
Evaluation: Accuracy metrics and confusion matrix analysis

Key Libraries

scikit-learn - Machine learning algorithms
librosa - Audio processing and feature extraction
pandas & numpy - Data manipulation
matplotlib & seaborn - Data visualization

Results Summary

Gender prediction achieves near-perfect accuracy (96.67%)
Emotion classification shows moderate success (70%) due to complexity
Combined classification performs similarly to emotion-only prediction
Optimization techniques provide significant improvement for emotion classification

Authors
Noah Nielsen, Young Min Park, Dylan Murphy, Elijah Pearce, Alex Colmenar
Developed for SDSU CS 450: Introduction to AI
