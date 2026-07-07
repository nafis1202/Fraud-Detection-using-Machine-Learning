This project is an end-to-end machine learning application for detecting fraudulent financial transactions. Using a dataset of over 6.3 million transaction records from Kaggle, I built and evaluated a fraud detection model that achieved 94% prediction accuracy.
The project covers the complete machine learning workflow—from data preprocessing and feature engineering to model training, evaluation, and deployment with a simple Streamlit web application.
Project Highlights
Built a fraud detection model with 94% accuracy
Processed and analyzed 6.3 million financial transactions
Performed data preprocessing and feature engineering
Compared and evaluated machine learning models
Created a reusable Scikit-learn pipeline
Deployed the trained model with Streamlit
Developed using Python and popular data science libraries
Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Joblib
Streamlit
Machine Learning Workflow
Data cleaning and preprocessing
Exploratory Data Analysis (EDA)
Feature engineering
Data encoding and scaling
Model selection and training
Model evaluation
Pipeline creation
Model deployment with Streamlit
Dataset
The dataset was obtained from Kaggle and contains 6.3 million financial transaction records used for fraud detection.
Transaction Types
CASH_IN – Depositing cash into an account through a merchant.
CASH_OUT – Withdrawing cash from an account through a merchant.
DEBIT – Transferring money from a mobile money account to a bank account.
PAYMENT – Paying merchants for goods or services.
TRANSFER – Sending money to another user within the mobile money platform.
The dataset also includes transactions that were incorrectly flagged by previous fraud detection systems, making it useful for developing more robust machine learning models.
Model Performance
Accuracy: 94%
The model was evaluated using standard classification metrics to measure its effectiveness in identifying fraudulent transactions while minimizing false positives.
Project Structure
Fraud-Detection/
│
├── data/
├── notebooks/
├── fraud_detection_pipeline.pkl
├── fraud_detection.py
├── requirements.txt
└── README.md
Streamlit Application
The project includes a Streamlit web application that allows users to:
Select a transaction type
Enter transaction details
Predict whether a transaction is fraudulent
Receive an easy-to-understand fraud prediction instantly
Future Improvements
Improve fraud detection using advanced feature engineering
Handle class imbalance with techniques such as SMOTE
Experiment with XGBoost, LightGBM, and CatBoost
Perform hyperparameter tuning
Deploy the application to Streamlit Community Cloud or another cloud platform
Add real-time fraud detection capabilities
Dataset Source
Dataset: Fraud Detection Dataset (Kaggle)
The dataset contains over 6.3 million financial transactions and is widely used for machine learning fraud detection research and practice.
Author
Nafis
If you found this project helpful, feel free to ⭐ the repository and share your feedback!
