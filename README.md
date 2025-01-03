# Machine_Learning_Project
## Bank Customer Churn Model
The notebook aims to build a model to predict customer churn for a bank using a Support Vector Machine (SVM) classifier. It addresses data encoding, feature scaling, handling imbalanced data, and hyperparameter tuning.

Data:

The notebook uses a bank customer churn dataset from a GitHub repository. The dataset includes customer information such as demographics, account details, and churn status.

Steps:

Data Preparation: The notebook starts with data loading, cleaning, and encoding categorical variables. It handles imbalanced data using both undersampling and oversampling techniques. Feature Engineering: Key features like 'CreditScore', 'Age', 'Tenure', 'Balance', and 'Estimated Salary' are standardized. Model Training: An SVM classifier is trained on the prepared data. The performance is evaluated using metrics like accuracy and classification report. Hyperparameter Tuning: Grid search is used to optimize the SVM model's hyperparameters to improve performance. Model Evaluation: The final model's performance is assessed using the test data.

Key Libraries Used:

pandas for data manipulation. NumPy for numerical operations. matplotlib and seaborn for visualization. scikit-learn for model building and evaluation. imblearn for handling imbalanced data.
