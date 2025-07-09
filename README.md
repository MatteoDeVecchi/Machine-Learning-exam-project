#  Airline Passenger Satisfaction – Classification ML Project

This project was developed as part of a Machine Learning exam assignment during my Artificial Intelligence studies.  
It focuses on predicting **passenger satisfaction** (Satisfied vs. Neutral/Dissatisfied) using structured flight and service data.

The task involves binary classification, feature preprocessing, model comparison, and evaluation — all implemented with real-world constraints typical of an academic setting.

---

##  Problem Statement

**Goal:**  
Build a machine learning model to classify airline passengers as "Satisfied" or "Neutral/Dissatisfied" based on:

- **Demographics:** Gender, Age
- **Travel details:** Customer Type, Type of Travel, Class, Flight Distance
- **Service ratings (scale 1–5):** Online Booking, Boarding, Seat Comfort, Cleanliness, Food & Drink, In-flight Service, Wifi, Entertainment, etc.
- **Delays:** Departure and Arrival Delay (in minutes)

---

##  Project Pipeline

1. **Data Preprocessing**
   - Handle categorical variables (LabelEncoding, OneHot)
   - Handle missing values
   - Normalize numerical features

2. **Model Training**
   - Logistic Regression
   - Random Forest
   - XGBoost
   - SVM (optional)

3. **Evaluation**
   - Accuracy, Confusion Matrix
   - ROC Curve, Precision-Recall
   - Cross-validation

4. **Conclusion**
   - Best model identified by comparing performance and robustness.

---

## Technologies Used

- Python, Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib, Seaborn

---

##  Academic Context

This was a final project for the **Machine Learning exam** in the second year of my AI degree.  
The assignment was completed under exam-style constraints (limited time, CPU-only environment).  
The emphasis was on correct pipeline design, appropriate modeling decisions, and result interpretation — not just raw accuracy.

---

##  Files

- `airline-satisfaction-classification.ipynb`: Main notebook with all code and analysis  
- `README.md`: This file  
