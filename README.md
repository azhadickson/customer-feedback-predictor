# 🧠 Customer Feedback Prediction

This project focuses on predicting whether a customer will leave **positive or negative feedback** for online food orders. Using features like age, income, and education, I built a classification model to analyze sentiment trends and evaluate baseline performance using **Naive Bayes**.

The goal was to explore how user demographics and behavior relate to feedback, and to test a simple, interpretable model for binary classification.

---

## 📂 Dataset

The dataset includes customer-level information from an online food ordering system:

- `Age`
- `Gender`
- `Marital Status`
- `Occupation`
- `Monthly Income`
- `Educational Qualifications`
- `Feedback` *(target: Positive or Negative)*

**Original file**: `onlinefoods.csv`

---

## 🧪 Methodology

### Data Exploration
- Loaded and inspected the dataset
- Visualized feedback distribution and age relationship using boxplots

### Feature Engineering
- Selected relevant predictors
- Encoded categorical variables (if applicable)

### Modeling
- Used **Multinomial Naive Bayes** from `scikit-learn`
- Split data into 80% training and 20% testing
- Evaluated using **accuracy**

---

## 📊 Results

- **Test Accuracy**: **80.77%**
- **Distribution Insight**: 
  - Positive feedback had a **lower median age (~24)** compared to negative feedback (~26)
  - Positive feedback showed a **wider age range**, suggesting more variability among satisfied users

---

## ✅ Key Takeaways

- **Younger users** are generally more likely to leave **positive feedback**
- **Age** appears to be a distinguishing factor in predicting sentiment
- **Naive Bayes** provided a quick, interpretable baseline for classification
- Visualization helped confirm feature relevance before training the model

