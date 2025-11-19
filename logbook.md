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
- Dataset includes demographic attributes, behavioral metrics, and ASD screening responses.  
- *(Dataset citation to be added as per instructor guidelines.)*

### Exploratory Data Analysis and Visualization
- Distribution plots for demographic features.  
- Correlation heatmaps showing relationships between attributes.  
- Visualization of class imbalance.  
- PowerBI/Tableau dashboards for feature-level insights.

### Algorithms Used
- Logistic Regression  
- Support Vector Classifier (SVC)  
- XGBoost Classifier  

---

## 4. Implementation Details
**Date: 29/09/2025 to 18/10/2025**

### Module 1: Data Preprocessing
- Handled missing values and performed label encoding.  
- Performed feature scaling using standardization.  
- Applied oversampling (e.g., SMOTE) to balance dataset classes.  

### Module 2: Model Development
- Implemented Logistic Regression, SVC, and XGBoost models.  
- Tuned hyperparameters for optimal performance.  
- Trained and validated models on split datasets.

### Module 3: Testing and Validation
- Evaluated the models on the test dataset.  
- Computed accuracy, precision, recall, and F1-score.  
- Generated confusion matrices for each algorithm.  

---

## 5. Results
**Date: 27/10/2025 to 04/11/2025**

### Results Summary
- XGBoost achieved the highest accuracy among all tested models.  
- SVC performed effectively, particularly in handling high-dimensional features.  
- Logistic Regression served as an interpretable baseline model.

### Performance Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

### Model Evaluation
- ROC curves for all algorithms.  
- Feature importance graph for XGBoost.  
- Comparative charts summarizing model performance across metrics.

---

## 6. Conclusion
The Autism Prediction System successfully demonstrates the potential of machine learning in early screening and risk identification for ASD. Among the evaluated models, XGBoost delivered superior performance. This system has strong potential to assist clinicians, educators, and early-intervention programs by providing an accessible, automated, and data-driven screening method.

---

## 7. References (IEEE Format)
1. Authors, “Title of Paper,” *Journal Name*, vol., no., year.  
2. Dataset Source, “Autism Screening Dataset,” year.  
3. Additional research papers (3–5 citations as per project requirement).
