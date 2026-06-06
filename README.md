# Imbalanced Disaster Tweet Classification

This project explores the challenge of imbalanced text classification using the Disaster Tweets dataset. Multiple machine learning models, including Logistic Regression, Random Forest, and Neural Networks, are trained and evaluated before and after applying imbalance handling techniques such as Class Weighting, Random Oversampling, and SMOTE.

The objective is to improve the detection of disaster-related tweets while maintaining balanced overall performance across evaluation metrics such as Recall, F1-Score, ROC-AUC, and PR-AUC.

## Project Workflow

### 1. Data Preprocessing

* Text cleaning and normalization
* Tokenization
* Stopword removal
* Stemming / Lemmatization

### 2. Feature Extraction

* TF-IDF Vectorization

### 3. Model Training

* Logistic Regression
* Random Forest
* Neural Network

### 4. Imbalance Handling

* Class Weighting
* Random Oversampling
* SMOTE

### 5. Evaluation

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* PR-AUC
* Confusion Matrix


## Key Findings

* Logistic Regression with SMOTE achieved the strongest overall performance in terms of Accuracy and F1-Score.
* Random Forest with Random Oversampling achieved the highest Recall for disaster tweet detection and the best ROC-AUC.
* Imbalance handling techniques significantly improved minority-class detection compared to baseline models.
* SMOTE and Random Oversampling provided the most effective improvements across evaluated models.


## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* PyTorch
* NLTK
* Imbalanced-Learn
* Matplotlib

## Project Structure

```text
disaster-tweet-classification/
│
├── data/
├── notebooks/
├── reports/
├── requirements.txt
└── README.md
```

## Dataset

Dataset Source: [Disaster Tweets Dataset (Kaggle)]

https://www.kaggle.com/datasets/vstepanenko/disaster-tweets/data

Download the dataset and place `tweets.csv` inside the `data/` directory before running the notebook.


## Installation

```bash
pip install -r requirements.txt
```

## Usage

Open and run:

```text
notebooks/disaster_tweet_classification.ipynb
```

using Jupyter Notebook.
