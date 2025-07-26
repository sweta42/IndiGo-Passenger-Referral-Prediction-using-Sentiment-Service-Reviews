# ✈️ IndiGo Passenger Referral Prediction using Sentiment & Service Reviews

![Python](https://img.shields.io/badge/Language-Python-blue)
![Machine Learning](https://img.shields.io/badge/ML-Classification-success)
![NLP](https://img.shields.io/badge/Technique-NLP-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📘 Overview

This project aims to **predict whether a passenger would recommend IndiGo Airlines** to others based on textual reviews and service-related features. We use **Natural Language Processing (NLP)**, **machine learning classification models**, and **model interpretation techniques** to draw meaningful insights and improve customer retention strategy.

It is developed as part of the **Capstone Project** in the AlmaBetter Data Science Program.

---

## 🎯 Problem Statement

With thousands of passenger reviews and feedback coming in, it becomes crucial for IndiGo Airlines to:
- Identify **patterns in customer satisfaction**
- Understand **which services impact recommendation**
- Predict **referral likelihood**
- Make data-driven improvements in their offerings

---

## 📂 Dataset Description

- Source: Provided in AlmaBetter Capstone Module
- Size: ~7,000 records
- Features include:
  - Text reviews (`Review`, `Review_Title`)
  - Ratings on parameters like `Cleanliness`, `Food`, `Staff Service`, `Entertainment`, etc.
  - Binary target column: `Recommended` (Yes/No)

---

## 🔧 Technologies & Libraries Used

| Category            | Tools / Libraries |
|---------------------|------------------|
| Language            | Python 3.x        |
| Data Processing     | Pandas, NumPy     |
| Visualization       | Matplotlib, Seaborn, WordCloud |
| NLP                 | NLTK, Scikit-learn (TF-IDF) |
| Models              | Logistic Regression, Random Forest, SVM |
| Model Evaluation    | Accuracy, Precision, Recall, F1-Score |
| Model Interpretation| SHAP (SHapley Additive Explanations) |
| Notebook Environment| Jupyter Notebook  |

---

## 🧠 Project Workflow

### 1. 🔍 **Exploratory Data Analysis (EDA)**
- Distribution of ratings and recommendation
- Correlation between service features and final decision
- Word clouds and sentiment trends in text reviews

### 2. ✨ **Data Preprocessing**
- Handling missing values
- Label encoding and normalization
- Text cleaning: lowercase, punctuation removal, stopword removal, stemming

### 3. 🧾 **Text Vectorization (NLP)**
- TF-IDF (Term Frequency - Inverse Document Frequency) applied to `Review` and `Review_Title`

### 4. 🧪 **Model Building**
Models trained using both numerical and text data:
- **Logistic Regression**
- **Random Forest**
- **Support Vector Machine (SVM)**

### 5. 📊 **Evaluation Metrics**
- Confusion Matrix
- Classification Report
- ROC-AUC Curve

### 6. 🔍 **Model Interpretability**
- Used **SHAP** to interpret feature importance and model predictions

---

## 🏆 Results

| Model                | Accuracy | F1-Score | ROC-AUC |
|----------------------|----------|----------|---------|
| Logistic Regression  | ~85%     | 0.84     | 0.88    |
| Random Forest        | ~87%     | 0.86     | 0.90    |
| SVM (linear kernel)  | ~84%     | 0.83     | 0.87    |

- **Random Forest** was selected as the final model due to its balance between accuracy and interpretability.

---

## 🔍 SHAP Insights

- **Review sentiment**, **cleanliness**, and **value for money** were top factors influencing passenger recommendation.
- Negative words like *“delayed”*, *“rude”*, or *“no refund”* reduced referral chances.
- Passengers appreciating *“on-time service”*, *“politeness”*, and *“comfort”* were likely to recommend.

---

## 📈 Business Impact

- Helps IndiGo Airlines **identify passengers at risk of churn**
- Offers actionable suggestions to improve key services
- Enhances **customer experience** and potential for **referral marketing**

---

## 📎 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/indigo-referral-prediction.git
   cd indigo-referral-prediction
   
## 🧑‍💻 Author

**Sweta Kumari**  
🎓 Data Science Enthusiast | AlmaBetter Capstone Contributor  
🔗 [LinkedIn](https://linkedin.com/in/your-link)  
💻 [GitHub](https://github.com/your-profile)

---

## 📄 License

This repository is licensed for educational use under the [MIT License](LICENSE). All rights to the dataset belong to AlmaBetter and its respective data providers.
