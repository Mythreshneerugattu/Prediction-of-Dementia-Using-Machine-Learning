# Prediction-of-Dementia-Using-Machine-Learning
Dementia affects millions, making early detection vital. This project uses machine learning on the OASIS dataset, applying robust preprocessing and models like Logistic Regression and Random Forest. With a 96% accuracy, it highlights data-driven healthcare solutions while addressing ethical data use.
# Features
Data Preprocessing:
Handled missing values with KNN imputation for enhanced accuracy.
Addressed outliers using capping techniques to retain data integrity.
Feature Engineering:
Employed F-statistics to identify the top 8 features contributing to dementia prediction.
Analyzed correlations to ensure independence and relevance of selected features.
Model Development:
Built and tested various machine learning models, including Logistic Regression, SVM, Random Forest, and KNN.
Experimented with Kernelized SVM using polynomial and RBF kernels.
Performance Metrics:
Evaluated models based on accuracy, precision, recall, and F1 score.
Logistic Regression emerged as the best-performing model, achieving an accuracy of 96%.
# Dataset
The OASIS dataset, a longitudinal study of 150 subjects aged 60 to 96 years, forms the foundation of this project. Key characteristics include:

Sample Composition: Nondemented, demented, and transitioning subjects.
Features: Neuroimaging data, demographic information, clinical assessments, and cognitive scores.
Longitudinal Nature: Multiple imaging sessions over time provide insights into cognitive health progression.
# Steps Completed
Data Preprocessing:
Handled null values using KNN imputer.
Mitigated outliers with capping (5th and 95th percentiles).
Feature Selection:
Identified key predictors: top 8 features based on F-statistics and correlation analysis.
Model Development:
Implemented machine learning models (Logistic Regression, Random Forest, KNN, Kernelized SVM, and others).
Evaluation:
Compared models using accuracy and other metrics.
Logistic Regression was the most accurate and balanced model.
# Results
Logistic Regression: 96% Accuracy (Best performing model)
Other Models:
Kernelized SVM (Polynomial Kernel): Moderate accuracy.
Kernelized SVM (RBF Kernel): Poor performance due to dataset-specific challenges.
# Challenges and Learnings
Handling null values and outliers required innovative solutions, such as KNN imputation and capping.
Kernel selection in SVM models significantly influenced their performance, emphasizing the need for dataset-specific tuning.
Ethical considerations in healthcare data management were a key focus.
# Future Scope
Extend the model to include additional datasets for enhanced generalization.
Collaborate with medical professionals for real-world testing and validation.
Develop a user-friendly application to support clinical decision-making.
