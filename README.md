# student-burnout-analytics
Behavioural Analytics system for early detection of student burnout and dropout risk using machine learning.
# Early Detection of Student Burnout & Dropout Risk

### Behavioural Analytics Hackathon Project

---

## Project Overview

Universities often recognize academic problems only after a student’s performance has already declined. By that stage, meaningful intervention becomes difficult.

This project focuses on **early detection** — using behavioural analytics and machine learning to identify warning signs of student burnout before serious academic consequences occur.

The system analyzes behavioural patterns such as learning activity, attendance trends, and submission habits to estimate a student’s burnout risk and recommend timely support actions.

---

## Project Goals

The objective of this project is to build a behavioural analytics model that can:

* Predict **Burnout Risk Level** (Low / Medium / High)
* Generate a **Student Risk Score (0–100)**
* Identify key behavioural factors influencing risk
* Suggest practical intervention strategies for educators

---

##  Project Approach

### Dataset

Due to privacy restrictions and limited access to real student behavioural data, a **synthetic dataset** was created to simulate realistic academic behaviour patterns.

**Dataset Type:** Synthetic
**Reason:** Real behavioural datasets involving students are confidential and not publicly accessible.

### Simulated Behavioural Features

The dataset includes:

* LMS login frequency (student engagement)
* Assignment submission delays
* Attendance rate
* Average sleep hours
* Sentiment score from feedback responses
* Weekly study hours

**Dataset Size:** 500 simulated students

Behavioural assumptions used during generation:

* Reduced platform activity may indicate disengagement
* Frequent submission delays suggest academic stress
* Declining attendance can signal burnout risk
* Negative sentiment reflects emotional strain

---

## Methodology

### Feature Engineering

Behavioural indicators were combined to construct a burnout risk score representing overall student wellbeing and engagement patterns.

### Machine Learning Model

**Random Forest Classifier**

This model was selected because it:

* Handles behavioural variability effectively
* Provides interpretable feature importance
* Performs well without heavy parameter tuning
* Is suitable for early-stage predictive systems

---

## System Outputs

The model produces:

* Burnout Risk Classification
* Numerical Risk Score (0–100)
* Behavioural Trigger Analysis
* Personalized Intervention Recommendations

### Example Interventions

* **High Risk:** Immediate counseling and academic advisor support
* **Medium Risk:** Mentoring and workload monitoring
* **Low Risk:** Continued engagement and progress tracking

---

## Behavioural Insights

Model analysis revealed several strong predictors of burnout:

* Increased assignment delays
* Lower attendance rates
* Reduced LMS engagement

These findings align with commonly observed behavioural warning signs in academic environments.

---

## Model Evaluation

Performance was evaluated using:

* Train–Test data split
* Accuracy score
* Classification report metrics

The model demonstrates reliable predictive capability for simulated behavioural data.

---

## Technology Stack

* Python
* Google Colab
* Pandas & NumPy
* Scikit-learn
* Matplotlib

---

## Repository Structure

```
student-burnout-analytics/
│
├── notebook.ipynb
├── student_burnout_data.csv
├── README.md
└── report.pdf
```

---

## Future Improvements

Potential extensions of this project include:

* Integration with real LMS platforms
* Real-time monitoring dashboards
* Explainable AI techniques (e.g., SHAP)
* Automated early-warning notification systems

---

## Author

Behavioural Analytics Hackathon Submission
Developed as part of a behavioural analytics challenge focusing on predictive decision intelligence.

---
