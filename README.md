# Chronic-Kidney-Disease
Predicting Chronic Kidney Disease using AutoML (AutoSklearn) on Docker container

Chronic Kidney Disease (CKD) is a significant health concern characterized by the gradual loss of kidney function over time, leading to the accumulation of waste and fluid in the body. The impact of CKD is extensive and far-reaching. It contributes to increased morbidity and mortality rates, impairing the quality of life for millions of individuals worldwide. CKD requires long-term management, and if left uncontrolled, it can progress to kidney failure, necessitating dialysis or kidney transplantation. The financial burden of CKD is significant, with substantial healthcare costs associated with diagnosis, treatment, and managing complications.

Through the analysis of large datasets and integration of various risk factors, machine learning algorithms can aid in the early detection of CKD. Early identification allows for timely interventions and the implementation of strategies to slow down or prevent disease progression. 

After defining and applying the needed data preprocessing and exploratory data analysis (EDA), a containerized application on Docker, making use of AutoML (AutoSklearn), allows us to automate the model selection and relative hyperparameter optimization, by setting the optimization metric we can explore and investigate the performance of various models and choose the one which is best suited to our problem.

Given the strong correlation of the disease's presence with specific features (exemplified by the correlation matrix in the EDA phase), the best models manage to obtain a Recall (Predicted number of CKD/Actual Number of CKD) ranges between 0.96 and 0.99 on the test set, indicating a model that is extremely precise in identifying CKD. The high values registered in the F-1 Score also testify a balance between Precision and Recall that ultimately benefits the healthcare system.
