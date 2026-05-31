# Detecting Spam Emails Using Machine Learning and Deep Learning

A comprehensive machine learning and deep learning project for classifying emails as spam or legitimate (ham). This repository implements multiple ML algorithms and neural network architectures to achieve high accuracy in spam detection.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models Implemented](#models-implemented)
- [Results](#results)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Contributing](#contributing)
- [License](#license)

## Overview

Email spam is a persistent problem affecting millions of users worldwide. This project develops and compares various machine learning and deep learning models to accurately classify emails as spam or legitimate. The solution uses natural language processing (NLP) techniques for feature extraction and multiple classification algorithms for optimal performance.

## Features

✅ **Multiple ML Algorithms**
- Naive Bayes
- Support Vector Machine (SVM)
- Logistic Regression
- Random Forest
- Decision Trees

✅ **Deep Learning Models**
- Artificial Neural Network (ANN)
- Recurrent Neural Network (RNN/LSTM)
- Convolutional Neural Network (CNN)

✅ **Text Preprocessing**
- Tokenization
- Stop word removal
- Lemmatization
- TF-IDF vectorization
- Word embeddings
- <img width="636" height="352" alt="image" src="https://github.com/user-attachments/assets/33e402c7-5b7d-49f1-9388-fc1096c3e55b" />
<img width="636" height="352" alt="image" src="https://github.com/user-attachments/assets/470e2d0e-539a-4ae7-8ea3-f35500e6fec8" />


✅ **Model Evaluation**

<img width="567" height="455" alt="image" src="https://github.com/user-attachments/assets/4551173b-dfe8-4601-838b-f49665a7cfe2" />
<img width="1359" height="740" alt="image" src="https://github.com/user-attachments/assets/80f0e337-7183-4a1e-91db-12f8de6c4bd5" />

- Accuracy, Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Curve
- Cross-validation

## Dataset

The project uses publicly available email spam datasets:
- **Spam Assassin Public Corpus** - Collection of spam and ham emails
- **UCI Machine Learning Repository** - Email spam classification dataset

### Data Statistics
- Total Emails: 5,572+
- Spam Emails: ~2,000
- Ham (Legitimate) Emails: ~3,000
- Class Distribution: Balanced dataset

## Installation

### Prerequisites
- Python 3.7+
- pip or conda

### Setup

```bash
# Clone the repository
git clone https://github.com/mudassar2224/Detecting-Spam-Emails-Using-Machine-Learning-and-deep-learning.git
cd Detecting-Spam-Emails-Using-Machine-Learning-and-deep-learning

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Usage

### 1. Data Preprocessing

```python
python src/preprocessing.py
```

This script:
- Loads the email dataset
- Cleans and preprocesses text
- Removes stop words and special characters
- Generates TF-IDF features

### 2. Training Machine Learning Models

```python
python src/train_ml_models.py
```

Trains and evaluates:
- Naive Bayes
- SVM
- Logistic Regression
- Random Forest
- Decision Trees

### 3. Training Deep Learning Models

```python
python src/train_dl_models.py
```

Trains and evaluates:
- Artificial Neural Network (ANN)
- LSTM (Long Short-Term Memory)
- CNN (Convolutional Neural Network)

### 4. Model Evaluation & Comparison

```python
python src/evaluate_models.py
```

Generates:
- Performance metrics comparison
- Feature importance analysis

### 5. Prediction on New Email

```python
python src/predict.py --email "your email text here"
```

## Models Implemented

### Machine Learning Models




## Results

### Key Findings

- **Best Performing Model**: LSTM with **97.6% accuracy**
- **Fastest Model**: Logistic Regression (inference time: <1ms)
  

### Visualizations

The project generates comprehensive visualizations:
- Accuracy comparison bar charts
- Learning curves
- Feature importance plots


```

## Requirements

```
pandas==1.5.3
numpy==1.24.3
scikit-learn==1.2.2
tensorflow==2.12.0
keras==2.12.0
matplotlib==3.7.1
seaborn==0.12.2
nltk==3.8.1
gensim==4.3.1
scipy==1.10.1
imbalanced-learn==0.10.1
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

**Muhammad Mudassar**

## Acknowledgments

- Spam Assassin Public Corpus for dataset
- UCI Machine Learning Repository
- scikit-learn, TensorFlow, and Keras communities
- Natural Language Processing libraries (NLTK, spaCy)

## Contact

For questions or suggestions, please open an issue or contact me at your-email@example.com

---

**Last Updated**: May 2026
**Status**: Active Development
