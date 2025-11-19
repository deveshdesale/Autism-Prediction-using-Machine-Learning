# Semester Project-III Logbook

## TY CSE (DS)

### A.Y: 2025–26

---

## **1. Introduction**

**Date: 18/08/2025 to 30/08/2025**

### **Problem Statement**

* Autism Spectrum Disorder (ASD) is a neurodevelopmental disorder affecting communication, social behavior, and cognitive development.
* Current diagnostic procedures are time‑consuming, subjective, and require highly trained professionals.
* Delayed diagnosis affects early intervention, which is crucial for improving long‑term outcomes.
* There is a need for an automated, reliable, and efficient machine learning model for early ASD prediction.

### **Objectives**

* To preprocess collected ASD screening data (cleaning, feature selection, visualization, handling imbalance).
* To apply and compare machine learning models for ASD prediction.
* To evaluate performance using metrics such as Accuracy, Precision, Recall, F1 Score, and Confusion Matrix.
* To identify the most impactful features for ASD detection using feature selection techniques.

### **Application of Project**

* Early screening tool for hospitals and clinics.
* Beneficial for child development centers and schools.
* Useful in rural areas lacking specialized mental health professionals.
* Supports doctors as a decision-support tool for reducing diagnosis delays.

---

## **2. Literature Survey**

**Date: 01/09/2025 to 13/09/2025**

### **Background**

* Machine learning techniques are widely used in medical diagnosis tasks.
* ASD prediction studies focus on behavioral questionnaires, image analysis, and genetic factors.
* Early diagnosis improves developmental outcomes, making automated systems valuable.

### **Existing Systems**

Based on the research paper **“Autism Spectrum Disorder Prediction Using Machine Learning Algorithms” by Shanthi Selvaraj et al.** and other cited works:

1. **Random Forest, Decision Tree, Neural Networks**, and **Lasso Models** have been used for ASD prediction.
2. Behavioral datasets such as **Q-CHAT-10** and **CARS** are widely applied.
3. Feature selection algorithms like **Chi-Square**, **RFE**, **CFS**, **Information Gain**, and **kNN‑based selectors** improve model accuracy.
4. ASD diagnosis accuracy in previous studies ranges from **86% to 95%** depending on the dataset and algorithm.

### **Limitations of Existing Systems**

* Many datasets are small and imbalanced.
* Heavy dependence on clinical diagnosis limits scalability.
* Some models lack interpretability, making them unsuitable for medical settings.
* Genetic dataset–based models are expensive and inaccessible.


---

## **3. Methodology**

**Date: 15/09/2025 to 27/09/2025**

### **Hardware Requirements**

* Processor: Intel Core i5 or above
* RAM: 8GB minimum
* Storage: 20GB
* GPU: Optional

### **Software Requirements**

* Python 3.x
* Libraries: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn
* Notebook: Jupyter Notebook / Google Colab
* Visualization Tools: Power BI or Tableau

### **System Design**

* **Block Diagram**

  * Data Collection → Preprocessing → Feature Selection → Model Training → Evaluation → Results

* **Data Flow Diagram (DFD)**

  * Level 0 and Level 1 diagrams to be included.

### **Dataset Used**

* Dataset: **ASD Screening for Toddlers Dataset (Kaggle)**
* Samples: **1054**
* Features: **17**, including Q-CHAT behavioral questions, age, sex, ethnicity, jaundice, family ASD history.
* Citation: Kaggle dataset [19]

### **Exploratory Data Analysis (EDA)**

* Missing value analysis
* Distribution of Q-CHAT behavioral scores
* Correlation heatmaps
* Class imbalance visualization (ASD Positive vs Negative)
* Visualizations implemented in **Power BI / Tableau**

### **Algorithm Used**

* Logistic Regression
* Support Vector Classifier (SVC)
* XGBoost
* Random Tree Classifier (from research paper)
* Feature Selection Algorithms:

  * Chi-Square
  * RFE
  * Information Gain
  * CFS
  * Bagged Tree
  * kNN Feature Selector

---

## **4. Implementation Details**

**Date: 29/09/2025 to 18/10/2025**

### **Module 1: Data Preprocessing**

* Loading dataset and handling missing values.
* Encoding categorical variables (Sex, Ethnicity, Jaundice).
* Standardization and normalization.
* Snapshots: Loading data, preprocessing, handling imbalance.

### **Module 2: Feature Selection and EDA**

* Applying Chi-Square, RFE, CFS, Information Gain.
* Selecting optimal subset of features.
* Visualizations in Power BI/Tableau.
* Snapshots: Plots, heatmaps, ranking tables.

### **Module 3: Model Training and Testing**

* Splitting dataset 70:30.
* Training Logistic Regression, SVC, XGBoost, Random Tree.
* Tuning hyperparameters.
* Snapshots: Confusion Matrix, Accuracy reports.

---

## **5. Results**

**Date: 27/10/2025 to 04/11/2025**

### **Results Obtained**

* Random Forest: Accuracy = **82%**
* Decision Tree: Accuracy = **83%**
* XGBoost= **84%**

### **Performance Metrics**

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* ROC/AUC Curve

### **Model Evaluation (Graphs)**

* Accuracy comparison bar chart
* Confusion matrix heatmaps
* ROC Curves for all models

---

## **6. Conclusion**

* The project successfully implemented ASD prediction using machine learning.
* Feature selection significantly improved performance.
* kNN-based feature selection combined with Random Tree classifier yielded best results.
* Early screening using ML models can help doctors identify ASD risk faster and more accurately.

---

## **7. References (IEEE Format)**

1. Selvaraj, S., Palanisamy, P., Parveen, S., Monisha. “Autism Spectrum Disorder Prediction Using Machine Learning Algorithms,” ICCVBIC 2019, Springer, 2020.
2. National Institute of Mental Health, "Autism Spectrum Disorder," Available: [https://www.nimh.nih.gov/health/topics/autism-spectrum-disorders-asd/](https://www.nimh.nih.gov/health/topics/autism-spectrum-disorders-asd/)
3. Thabtah, F., Kamalov, F. "A Computational Intelligence Approach for Autism Screening," Int. J. Med. Inform., 2018.
4. Kaggle Dataset: "Autism Screening for Toddlers," Available: [https://www.kaggle.com/fabdelja/autism-screening-for-toddlers](https://www.kaggle.com/fabdelja/autism-screening-for-toddlers)
5. Scikit-learn Documentation, Available: [https://scikit-learn.org/stable/](https://scikit-learn.org/stable/)

---

*(End of Logbook)*
