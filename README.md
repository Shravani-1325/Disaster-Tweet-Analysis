# 🚨 Disaster Tweet Analysis 🐦

## 📋 Project Overview
The goal of this project is to develop a machine learning model using Natural Language Processing (NLP) techniques to accurately classify tweets as either describing a real disaster (1) or not (0).

## 🌟 Objectives
- Understand and implement EDA for unstructured datasets.
- Build a predictive model for Disaster Tweet Analysis.
- Use CRISP-DM methodology for project structuring.
- Evaluate the model using key metrics like accuracy, precision, recall, and F1-score.

## 📊 Methodology - CRISP-DM
### 🔍 1. Business Understanding
This project aims to build a model to identify whether tweets are announcing disasters.

### 📊 2. Data Understanding
- **Source**: Kaggle - *Disaster Tweets Dataset* dataset.
- **Training Set**: 7613 rows and 5 columns.
- **Test Set**: 3263 rows and 4 columns..

### 🛠️ 3. Data Preparation
- **EDA (Exploratory Data Analysis)**:
    -   Distribution of disaster vs. non-disaster tweets before and after data preprocessing.
    -   Analysis of tweet lengths with **density curves**.
- **Text Preprocessing**:
    -   Removal of **stop words** and **punctuation**.
    -   **Tokenization** for breaking text into individual words.
- **Feature Engineering**:
    -   Applied **TF-IDF** and **Word2Vec** for text vectorization.

### 🤖 4. Model Training
Tested algorithms like **Logistic Regression**, **Random Forest**, and **Decision Trees**.

### 📈 5. Model Evaluation
- Metrics used:
-   Accuracy ✅
-   Precision 🏹
-   Recall 🔄
-   F1 Score 📊

## 🔍 Key Insights

### 1️⃣ EDA Findings

-   **Tweet Distribution**:
    -   **Before Modeling**: The dataset had an imbalance in disaster (1) vs. non-disaster (0) tweets.
    -   **After Modeling**: The balance was slightly adjusted after preprocessing and sampling.
-   **Tweet Length**:
    -   Disaster tweets tend to have a longer distribution compared to non-disaster tweets.

### 2️⃣ Model Results

-   The **Logistic Regression** model performed the best, achieving:
    -   **Accuracy**: 72.49% 🎯
    -   **F1 Score**: 0.76 📈
    -   Confusion Matrix:
        -   True Positives (TP): 413 ✅
        -   True Negatives (TN): 678 ✅
        -   False Positives (FP): 185 ❌
        -   False Negatives (FN): 229 ❌
        

## 🚀 Tools and Technologies

-   **Python 🐍**
-   **Libraries**: Pandas, NumPy, Matplotlib, Scikit-learn, NLTK, Word2Vec
-   **NLP Techniques**: TF-IDF, Stop Words Removal, Tokenization
-   **Algorithms**: Logistic Regression, Random Forest, Decision Trees

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/housing-price-prediction.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the training script:
   ```bash
   python train.py
   ```

## 🌟 Future Scope

-   Explore deep learning models like **BERT** or **LSTM** for improved accuracy.
-   Build a web interface to classify new tweets in real-time.
