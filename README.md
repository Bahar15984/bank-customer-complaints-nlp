# bank-customer-complaints-nlp
NLP project to classify consumer complaints into banking product categories using Python, TF-IDF, and machine learning.
#  Bank Customer Complaints - NLP Classification

## Overview
This project applies **Natural Language Processing (NLP)** and **Machine Learning** techniques to automatically classify **consumer complaints** into specific banking product categories.  
The dataset is based on the **Consumer Financial Protection Bureau (CFPB)** complaints database.

This automation can help **financial institutions** and **regulatory agencies**:
- Categorize complaints more efficiently
- Prioritize urgent issues
- Improve customer service response times

---

##  Objective
- **Input:** Consumer complaint narrative (free-text)
- **Output:** Predicted banking product category (e.g., Mortgage, Credit Card, Student Loan)
- **Goal:** Improve operational efficiency by automating the classification process

---

##  Dataset
**Source:** Consumer Financial Protection Bureau (CFPB) – Public Database  

**Features:**
- `consumer_complaint_narrative` → Text of the complaint (main input)
- `product` → Target label (e.g., Mortgage, Credit Card, Student Loan)

## Dataset Access
The dataset used in this project is publicly available from the **Consumer Financial Protection Bureau (CFPB)** Consumer Complaint Database.

You can download it here:  
 [CFPB Consumer Complaint Database](https://www.consumerfinance.gov/data-research/consumer-complaints/)

After downloading:
1. Save the file as `consumer_complaints.csv` in the project folder.
2. Run the Jupyter Notebook to reproduce the results.

**Features:**
- `consumer_complaint_narrative` → Text of the complaint (main input)
- `product` → Target label (e.g., Mortgage, Credit Card, Student Loan)

---

##  Methodology
1. **Data Cleaning & Preprocessing**
   - Lowercasing
   - Removing punctuation & special characters
   - Tokenization
   - Stopword removal
   - Lemmatization
2. **Feature Engineering**
   - TF-IDF Vectorization
3. **Modeling**
   - Logistic Regression
   - Random Forest Classifier
   - XGBoost Classifier
4. **Evaluation Metrics**
   - Accuracy
   - Precision, Recall, F1-score
   - Confusion Matrix

---

##  Results
- **Best Model:** XGBoost Classifier
- **Macro F1-score:** `XX.XX%`
- **Accuracy:** `XX.XX%`
- Model performance improved significantly after text preprocessing and feature extraction with **TF-IDF**.

---

## Tech Stack
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, NLTK, TextBlob
- **Tools:** Jupyter Notebook

---

##  How to Run
1. **Clone the repository:**
```bash
git clone https://github.com/Bahar15984/bank-customer-complaints-nlp.git
cd bank-customer-complaints-nlp

