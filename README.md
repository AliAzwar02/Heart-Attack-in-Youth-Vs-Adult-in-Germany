# Heart Attack Prediction in Youth vs Adults (Germany)

## 📖 Project Overview
This project focuses on predicting heart attack incidence using **machine learning techniques** with a special comparison between **youth** and **adult** populations in Germany.  
The dataset includes **275,000+ records** with demographic, lifestyle, and health-related features.

We applied **Exploratory Data Analysis (EDA)**, feature selection, and implemented multiple classifiers:
- **Support Vector Machine (SVM)**
- **Naïve Bayes**
- **K-Nearest Neighbors (KNN)**

The project highlights key health and lifestyle factors contributing to heart attacks and evaluates model performance across different algorithms.

---

## ⚙️ Methodology
1. **Data Cleaning & Preprocessing**
   - Removed duplicates, handled missing values
   - Standardized numerical features (BMI, Cholesterol, Alcohol Consumption)
   - Encoded categorical variables (Smoking, Diet Quality, Education Level)

2. **Exploratory Data Analysis (EDA)**
   - Histograms, boxplots, scatter plots
   - Correlation heatmaps
   - Identification of key risk factors

3. **Modeling**
   - Implemented SVM (linear & RBF kernel)
   - Compared with Naïve Bayes and KNN
   - Hyperparameter tuning for optimization

4. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix
   - ROC Curve & AUC

---

## 📊 Results
| Model        | Accuracy | Precision | Recall | F1-Score |
|--------------|----------|-----------|--------|----------|
| **SVM**      | 0.48     | 0.48      | 0.71   | 0.58     |
| **Naïve Bayes** | 0.57     | 0.55      | 0.70   | 0.62     |
| **KNN (k=3)** | 0.48     | 0.49      | 0.59   | 0.53     |

- **Naïve Bayes** performed best overall.
- **SVM** had high recall but low precision.
- **KNN** showed weaker balance compared to others.

---
