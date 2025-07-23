# ML_BreastCancer_Project
Breast Cancer project using the Wisconsin Breast Cancer Dataset, applying multiple machine learning models (including ANN and PSO+ANN), and replicating + enhancing work from the research paper
# 🧠 Breast Cancer Prediction: A Comparative Study Using Machine Learning Techniques

This project presents a comparative study of multiple machine learning models applied to the **Wisconsin Breast Cancer Dataset**, based on the research paper:

> **"Breast Cancer Prediction: A Comparative Study Using Machine Learning Techniques"**  
> Md. Milon Islam, Md. Rezwanul Haque, Hasib Iqbal, Md. Munirul Hasan, Mahmudul Hasan, Muhammad Nomani Kabir  
> Published by Springer Nature, 2020

---

## 📊 Objective

To predict breast cancer (malignant vs benign) using various machine learning techniques and compare their performance based on metrics like **Accuracy, Precision, Recall, F1 Score, Specificity,** and **MCC**.  
This project also integrates **advanced future work** by incorporating **PSO (Particle Swarm Optimization) with ANN** for enhanced performance.

---

## 📁 Dataset

- **Dataset:** Wisconsin Breast Cancer Dataset
- **Source:** UCI Machine Learning Repository
- **Attributes:** 30 features (mean, standard error, and worst of cell nuclei features)
- **Target Variable:** Diagnosis (M = Malignant, B = Benign)

---

## 🛠️ Techniques Used

The following models were implemented and compared:

| Model               | Type             |
|--------------------|------------------|
| Logistic Regression| Traditional ML   |
| SVM                | Traditional ML   |
| Random Forest      | Ensemble ML      |
| K-Nearest Neighbors| Traditional ML   |
| ANN (Original)     | Deep Learning    |
| PSO + ANN          | Hybrid AI        |

---

## 📈 Evaluation Metrics

The following metrics were used to evaluate each model:

- Accuracy
- Precision
- Recall
- F1 Score
- Specificity
- Matthews Correlation Coefficient (MCC)

> **Note:** CNN was initially tested but later excluded from the final comparison.

---

## 📊 Key Findings

- **PSO + ANN** outperformed all other models with the **highest accuracy (0.9917)** and **perfect specificity (1.0)**.
- Compared to the original ANN model:
  - Accuracy improved by **+1.72%**
  - Specificity increased from **0.9517** to **1.0**
  - MCC improved from **0.9326** to **0.9833**
- Traditional models like **KNN** and **SVM** also performed well, but hybrid models offered better robustness and generalization.

---

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/breast-cancer-prediction.git
   cd breast-cancer-prediction
