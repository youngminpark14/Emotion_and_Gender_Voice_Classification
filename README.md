# Voice Classification by Gender and Emotion
## Project Overview
This project implements machine learning classifiers to predict speaker gender and emotion from voice samples using Support Vector Machines (SVM). The analysis includes multiple languages (English, German, Spanish, Russian) and compares accuracy across different prediction scenarios.

## Datasets

- **EmoDB**: Berlin Database of Emotional Speech (German)
- **RAVDESS**: Ryerson Audio-Visual Database of Emotional Speech and Song

## Technical Implementation

- **Feature Extraction**: Mel-Frequency Cepstral Coefficients (MFCCs) using Librosa
- **Algorithm**: Support Vector Machines with linear and RBF kernels
- **Preprocessing**: StandardScaler normalization
- **Optimization**: GridSearchCV for hyperparameter tuning
- **Evaluation**: Accuracy metrics

## Key Libraries

- **scikit-learn**: Machine learning algorithms
- **librosa**: Audio processing and feature extraction
- **pandas & numpy**: Data manipulation
- **matplotlib & seaborn**: Data visualization

## Results Summary

- Gender prediction achieves near-perfect accuracy (96.67%)
- Emotion classification shows moderate success (70%) due to complexity
- Combined classification performs similarly to emotion-only prediction
- Optimization techniques provide significant improvement for emotion classification

## Authors
- Noah Nielsen, Young Min Park, Dylan Murphy, Elijah Pearce, Alex Colmenar
