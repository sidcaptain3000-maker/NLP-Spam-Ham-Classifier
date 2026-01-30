# NLP Spam-Ham Email Classifier

An end-to-end Machine Learning project that classifies emails as **Spam** or **Ham** (Legitimate) using Natural Language Processing (NLP).

## 1. Project Objective
The goal of this project is to build a classification model that accurately identifies unsolicited and unwanted emails using text preprocessing and the Multinomial Naive Bayes algorithm.

## 2. How it Works
1. **Preprocessing**: Text is cleaned by removing special characters, converting to lowercase, and removing "stopwords" (common words like 'the', 'is', etc.).
2. **Vectorization**: Using `TfidfVectorizer`, text data is converted into numerical features based on word importance.
3. **Modeling**: A Naive Bayes classifier is trained on the vectorized data.
4. **Evaluation**: The model is tested for accuracy and precision using a confusion matrix.



## 3. Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/spam-classifier.git](https://github.com/YOUR_USERNAME/spam-classifier.git)
