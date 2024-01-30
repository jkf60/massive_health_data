# Patient Mortality Prediction 

Overview

The final project for Group 1 focuses on using Electronic Health Records (EHR) to predict patient mortality within 180 days of their last exam. The project emphasizes the utility of EHR data in precision medicine and healthcare analytics.

Project Goal

To develop a machine learning model that can predict whether a patient will pass away within 180 days of their last recorded exam using EHR data.

Data and Methods

The project utilized a synthetic dataset created by the Centers for Medicare and Medicaid Services, converted to the OMOP Common Data Model. The team selected relevant clinical features for prediction, including demographics, patient diagnoses, medication records, and the Charlson Comorbidity Index (CCI).

Key Results

The model was trained to predict patient mortality with a focus on patients with Congestive Heart Failure (CHF).
Despite achieving a high accuracy of 95%, the AUC-ROC curve was low (0.48), indicating the model's limitations in distinguishing between patients who would pass away within 180 days and those who would not.

Graphs and Figures

1. Figure 1: Charlson Comorbidity Index (CCI) Scoring Criteria.
2. Figure 2: Feature Importance calculated using the F1-score.

Conclusion

The project highlights the challenges in developing predictive models using EHR data, especially in the context of imbalanced datasets. It underscores the need for improved modeling techniques and feature selection in healthcare analytics.
