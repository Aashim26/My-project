# My-project
🩺 HEALTHCARE DATA ANALYSIS FOR DISEASE PREDICTION 
📘 Overview
The Healthcare data analysis for disease prediction system  is a machine learning-based web application designed to predict the likelihood of various diseases based on user-input medical data. This system aims to assist users in identifying potential health risks and encourages early medical consultation.

🔍 Features
Predicts multiple diseases including:

Diabetes

Heart Disease

Parkinson’s Disease

Clean and user-friendly web interface

Real-time predictions using trained machine learning models

Interactive result visualization

⚙️ Technologies Used
🧠 Machine Learning
Python

Pandas, NumPy

Scikit-learn

Joblib for model serialization

🌐 Web Development
Streamlit (for the frontend UI)

HTML/CSS (optional styling)

🧪 Datasets Used
Diabetes: PIMA Indian Diabetes Dataset

Heart Disease: UCI Heart Disease Dataset

Parkinson’s Disease: UCI Parkinson’s Dataset

All datasets are cleaned and preprocessed before model training.

🚀 How to Run the Project

 streamlit run"C:\Users\91890\Desktop\multiple disease prediction\app.py"

🧠 Model Accuracy (Sample)

Disease	Algorithm Used	Accuracy
Diabetes	Random Forest	88%
Heart Disease	Logistic Regression	85%
Parkinson’s Disease	SVM	89%
Accuracy may vary based on training/testing splits and hyperparameter tuning.

📂 Project Structure
perl
Copy code
multiple-disease-prediction-system/
│
├── app.py                     # Main Streamlit app
├── diabetes_model.pkl         # Trained model for diabetes
├── heart_model.pkl            # Trained model for heart disease
├── parkinsons_model.pkl       # Trained model for Parkinson’s
├── requirements.txt           # Python dependencies
├── README.md                  # Project documentation
└── datasets/                  # All training datasets




📌 Future Improvements
Add more diseases and expand dataset variety

Integrate with health APIs for real-time data

Deploy on cloud (Heroku, AWS, etc.)




🙌 Acknowledgements
UCI Machine Learning Repository

Streamlit Community

Scikit-learn Documentation

