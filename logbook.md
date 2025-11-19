```md
# Semester Project-III Logbook
## TY CSE (DS)
### A.Y: 2025-26

---

## 1. Introduction
**Date: 18/08/2025 to 30/08/2025**

### Problem Statement
Autism Spectrum Disorder (ASD) is a neurodevelopmental condition that affects communication, social behavior, and learning abilities. Current diagnostic procedures rely on subjective human evaluation, are time-consuming, and lack standardization. Delays in diagnosis reduce opportunities for early intervention, which is crucial for positive developmental outcomes. Therefore, there is a need for an automated, machine-learning–based system to support early ASD screening.

### Objectives
- Perform data preprocessing including cleaning, feature engineering, class balancing, and standardization.  
- Implement machine learning algorithms such as Logistic Regression, Support Vector Classifier, and XGBoost.  
- Evaluate and compare model performance to identify the most accurate and reliable approach.

### Applications of the Project
- Early screening tool in hospitals and pediatric clinics.  
- Support for schools and child-development centers to identify children at risk.  
- Useful for rural and resource-limited areas with minimal specialist access.  
- Assists healthcare professionals by reducing manual workload and enhancing decision-making accuracy.

---

## 2. Literature Survey
**Date: 01/09/2025 to 13/09/2025**

### Background
Machine learning has become an essential tool in healthcare applications such as early disease prediction, classification, and risk assessment. ASD detection research leverages behavioral, demographic, and clinical features. Integration of multiple attributes contributes to higher prediction accuracy but introduces issues like imbalance and dataset limitations.

### Existing Systems (Research Review)
- Studies using behavioral questionnaires show improved screening but limited generalizability to wider populations.  
- Models such as SVM, Random Forest, and XGBoost demonstrate high accuracy but depend heavily on dataset size and diversity.  
- Recent research stresses the importance of scalable and accessible ML-based ASD assessment tools.

### Limitations of Existing Systems
- Small and limited datasets reduce model generalization capability.  
- Imbalanced class distribution biases model prediction.  
- Limited accessibility and lack of user-friendly interfaces in real clinical settings.  
- Insufficient integration of advanced ML models with real-world deployment environments.

### Citations (IEEE Format)
1. S. Selvaraj et al., “Autism Spectrum Disorder Prediction Using Machine Learning Algorithms,” ICCVBIC, 2020.  
2. National Institute of Mental Health, “Autism Spectrum Disorders,” https://www.nimh.nih.gov/health/topics/autism-spectrum-disorders-asd  
3. F. Thabtah et al., “A computational approach to detect autistic features,” Int. J. Med. Inform., 2018.  
4. Kaggle Dataset: Autism Screening for Toddlers. https://www.kaggle.com

---

## 3. Methodology
**Date: 15/09/2025 to 27/09/2025**

### Hardware Requirements
- Standard computing system  
- Minimum 8 GB RAM  
- Multicore processor  

### Software Requirements
- Python  
- Jupyter Notebook  
- Scikit-learn  
- XGBoost  
- PowerBI or Tableau (for visualization)

### System Design
- **Block Diagram:**  
  Data Acquisition → Preprocessing → Model Selection → Training → Evaluation → Deployment  
- **Data Flow Diagram:**  
  Level-0 and Level-1 DFD illustrating dataset flow, preprocessing operations, and model training pipeline.

### Dataset Used
- Autism Screening Dataset from an open-source repository.  
- Includes demographic attributes and screening responses.  
- *(Dataset citation to be added as per instructor guidelines.)*

### Exploratory Data Analysis and Visualization
- Distribution plots for demographic features.  
- Correlation heatmaps showing attribute relationships.  
- Visualization of class imbalance.  
- PowerBI/Tableau dashboards.

### Algorithms Used
- Logistic Regression  
- Support Vector Classifier (SVC)  
- XGBoost Classifier  

---

## 4. Implementation Details
**Date: 29/09/2025 to 18/10/2025**

### Module 1: Data Preprocessing
- Handled missing values and performed label encoding.  
- Feature scaling using standardization.  
- Applied oversampling (e.g., SMOTE) to balance dataset classes.  

### Module 2: Model Development
- Implemented Logistic Regression, SVC, and XGBoost.  
- Tuned hyperparameters.  
- Trained and validated using split datasets.

### Module 3: Testing and Validation
- Evaluated models on the test dataset.  
- Computed accuracy, precision, recall, and F1-score.  
- Generated confusion matrices.  

---

## 5. Results
**Date: 27/10/2025 to 04/11/2025**

### Results Summary
- XGBoost achieved the highest accuracy.  
- SVC performed effectively with high-dimensional data.  
- Logistic Regression provided an interpretable baseline.  

### Performance Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

### Model Evaluation
- ROC curves.  
- Feature importance graph (XGBoost).  
- Comparative charts across metrics.  

---

## 6. Conclusion
The Autism Prediction System demonstrates the potential of machine learning in early ASD risk identification. XGBoost delivered the best overall performance. This system can assist clinicians, educators, and intervention programs by providing an automated, data-driven screening method.

---

## 7. References (IEEE Format)
1. S. Selvaraj et al., “Autism Spectrum Disorder Prediction Using Machine Learning Algorithms,” ICCVBIC, 2020.  
2. NIMH, “Autism Spectrum Disorders,” https://www.nimh.nih.gov  
3. Kaggle Dataset: Autism Screening for Toddlers. https://www.kaggle.com  
4. Han & Kamber, *Data Mining: Concepts and Techniques*.  
5. Pedregosa et al., “Scikit-learn: Machine Learning in Python,” JMLR, 2011.
```
