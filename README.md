# 💳 Credit Card Fraud Detection

## 🧠 Project Objective
To build a robust machine learning model that detects **fraudulent credit card transactions** and helps prevent financial loss. This project focuses on solving a real-world problem using **classification techniques** under **highly imbalanced data** conditions.

---

## 📂 Dataset Information
The dataset used is from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud) and contains transactions made by **European cardholders** in **September 2013**.

- 📊 **Total Transactions**: 284,807  
- 🚨 **Fraudulent Transactions**: 492  
- ⚖️ **Class Imbalance**: Fraudulent cases represent **only 0.172%** of all transactions.

**Features:**
- 28 anonymized principal components from **PCA**: `V1, V2, ..., V28`
- `Time`: Time elapsed from the first transaction  
- `Amount`: Transaction amount  
- `Class`: Target variable (1 = Fraud, 0 = Genuine)

> 🧩 Due to confidentiality, original features are not disclosed.

---

## 🛠️ Tools & Technologies Used
This project was developed using the following tools and libraries:

| Category         | Tools & Libraries |
|------------------|-------------------|
| Language         | Python 🐍         |
| ML Frameworks    | TensorFlow, Keras |
| Algorithms       | Logistic Regression, SVM, Decision Tree, K-Nearest Neighbors |
| Evaluation       | AUC, PR-AUC, F1 Score |
| Data Handling    | Pandas, NumPy      |
| Visualization    | Seaborn, Matplotlib |
| Model Evaluation | Confusion Matrix, ROC, Precision-Recall Curve |

---

## 🧪 Techniques & Evaluation

- ✅ **Supervised Learning Classification Models**:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Decision Tree
  - K-Nearest Neighbors (KNN)
  - Neural Networks (TensorFlow + Keras)

- 📈 **Performance Metrics**:
  - **Precision-Recall Curve (PR AUC)**: Best suited for imbalanced data
  - **F1 Score**: Harmonic mean of precision and recall
  - **ROC AUC**: Evaluates the true positive rate vs false positive rate
  - ⚠️ *Confusion matrix accuracy alone is not meaningful due to class imbalance.*

---

## 📌 Key Takeaways

- Successfully applied multiple classification algorithms to detect fraud.
- Understood the significance of using **AUPRC** over accuracy in unbalanced datasets.
- Visualized model performance using **ROC curves** and **PR curves**.
- Learned how to balance precision and recall to minimize false positives and negatives.

---

## ✨ Future Improvements

- Try **SMOTE** or other resampling techniques to balance classes.
- Implement **ensemble methods** like Random Forest or XGBoost.
- Deploy the model with a Flask/Django web interface.
- Integrate with real-time APIs for fraud detection.

---

## 👨‍💻 About Me
I'm **Ritesh Kaushik**, an aspiring AI Engineer and certified Data Scientist.  
📍 Bengaluru | 🧠 Passionate about AI, ML & Deep Learning  
🔗 [LinkedIn](https://www.linkedin.com/in/riteshkaushik18/) | 💻 [GitHub](https://github.com/riteshkaushikbr)

---

> 🌟 *"Building smarter systems that detect the unseen — one dataset at a time."*
