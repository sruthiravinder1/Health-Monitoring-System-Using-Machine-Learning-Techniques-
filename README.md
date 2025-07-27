# Health-Monitoring-System-Using-Machine-Learning-Techniques-
This is a web-based health monitoring and disease prediction system built using **Python**, **Flask**, and **Machine Learning**. It allows patients to register, input symptoms, and receive predicted diseases using trained ML models. Doctors can view, accept, or reject appointments, and the admin can manage users and ratings.
# Features

-  Patient and Doctor Registration & Login
- Symptom-based Disease Prediction using ML
- Evaluation of ML models (RF, NB, DT, Voting Classifier)
- Doctor Appointment Booking System
- Rating System for Doctors
- Profile Image Upload using Base64
- Secure sessions using Flask
- Visualizations of ML model metrics (Accuracy, Precision, Recall, F1-score)
# Tech Stack

- **Frontend:** HTML, CSS (via Flask templates)
- **Backend:** Python, Flask
- **ML Libraries:** Scikit-learn, NumPy, Matplotlib, Pandas
- **Database:** MySQL (via custom `DBConnection.py`)
- **Other Tools:** OpenCV, PIL, Base64, Session Management

# ML Evaluation Module

The project includes an `evaluation_ml()` module that evaluates:
- Accuracy
- Precision
- Recall
- F1-Score

Across classifiers like:
- Random Forest (RF)
- Naive Bayes (NB)
- Decision Tree (DT)
- Voting Classifier

Plots are saved in `/static/` directory for UI display.

# How to Run the Project

# 1. Clone the Repository
git clone https://github.com/sruthiravinder1/Health-Monitoring-System-Using-Machine-Learning-Techniques-.git
cd Health-Monitoring-System-Using-Machine-Learning-Techniques-
