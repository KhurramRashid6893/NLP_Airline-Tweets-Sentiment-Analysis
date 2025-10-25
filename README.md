# ✈️ Airline Tweets Sentiment Analysis (NLP + Machine Learning)

This project analyzes airline-related tweets to determine public sentiment — **positive**, **negative**, or **neutral** — using Natural Language Processing (NLP) and Machine Learning techniques. It involves data cleaning, text vectorization with TF-IDF, and classification using Naive Bayes and Logistic Regression.

---

## 🗂️ Steps to Follow

1. **Loading and Exploring Data**  
   - Import the dataset and inspect tweet text distribution and sentiment balance.  

2. **Text Cleaning**  
   - Remove URLs, mentions, special characters, and stopwords.  
   - Convert text to lowercase and normalize white spaces.  

3. **Data Preparation**  
   - Tokenization and lemmatization for standardizing words.  

4. **Label Encoding**  
   - Encode sentiment labels (positive, neutral, negative) into numeric form.  

5. **Split Data**  
   - Divide the dataset into training and testing sets for evaluation.  

6. **Feature Engineering using TF-IDF**  
   - Convert tweet text into numerical vectors capturing word importance.  

7. **Model Building**  
   - Train and evaluate multiple ML models for sentiment classification:  
     - **Naive Bayes**  
     - **Logistic Regression**  

8. **Model Building Summary**  
   - Compare accuracy, precision, recall, and F1-score of both models.  

9. **Final Sentiment Analysis Pipeline**  
   - Build an end-to-end pipeline that takes raw tweets and outputs predicted sentiment.

---

## 🚀 Features
- Robust preprocessing of social media text  
- TF-IDF–based feature extraction  
- Multiple classifier comparison (Naive Bayes, Logistic Regression)  
- Visual analysis of sentiment distribution  
- Scalable pipeline for real-time tweet analysis  

---

## 🧩 Tech Stack
**Python** • **Pandas** • **NumPy** • **Scikit-learn** • **NLP** • **TF-IDF** • **Matplotlib / Seaborn**

---

## 🧭 Future Enhancements
- Integrate **Transformer-based models** (BERT, RoBERTa)  
- Deploy web app for real-time tweet sentiment detection  
- Add multi-language sentiment support  

---

⭐ *Developed to understand real-time customer emotions from airline-related tweets using NLP and ML.*
