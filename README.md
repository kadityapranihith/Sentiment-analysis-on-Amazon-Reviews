# Amazon Alexa Reviews Sentiment Analysis

This project classifies Amazon Alexa product reviews into positive or negative sentiments using machine learning and NLP techniques.

---

## 📊 Dataset  
The dataset is sourced from Kaggle:  
[Amazon Alexa Reviews Dataset](https://www.kaggle.com/datasets/sid321axn/amazon-alexa-reviews/data)

---

## 🔧 Project Workflow

### Data Preprocessing  
- Cleaned text data using **spaCy**: removed stopwords, punctuation, and applied lemmatization  
- Converted text to numerical features with **CountVectorizer**  
- Addressed class imbalance using **SMOTE** oversampling  

### Model Training & Hyperparameter Tuning  
- Models used:  
  - Random Forest  
  - Support Vector Machine (SVM)  
  - Multinomial Naive Bayes  
- Performed hyperparameter tuning with **GridSearchCV**  

### Evaluation  
- Achieved highest accuracy (~95%) with Random Forest  
- Generated classification report and confusion matrix  
- Visualized confusion matrix using **seaborn**  

---

## 🚀 Tech Stack  
- Python  
- pandas  
- spaCy  
- scikit-learn  
- imbalanced-learn (SMOTE)  
- seaborn & matplotlib  



