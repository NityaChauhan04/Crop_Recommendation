
# Project Title

A brief description of what this project does and who it's for

# 🌾 Crop Recommendation System
A machine learning-based system that predicts the most suitable crop to cultivate based on soil and weather conditions. This application helps farmers and agricultural experts make data-driven decisions for improving yield and profitability.

---

## 🎯 Objective

To recommend the optimal crop for cultivation based on environmental conditions using a classification machine learning model trained on historical agricultural data.

---

## 📊 Dataset Overview

* **Source:** Public Dataset (Kaggle or similar)

### Features:

*   N – Nitrogen content in soil
* P – Phosphorus content in soil
* K – Potassium content in soil
* temperature – Average temperature (°C)
* humidity – Relative humidity (%)
* ph – pH value of the soil
* rainfall – Rainfall in mm
* **Target:** label – Crop name

### Preprocessing:

* Missing Values: Checked and confirmed none present.
* Label Encoding: Crop names converted into numeric labels.
* Scaling: Applied StandardScaler to normalize feature distributions.
* Train-Test Split: 70% data for training, 30% for testing using train_test_split().

---

## 🤖 Model Development

### Models Evaluated:

* **Support Vector Machine (SVM)**
* **Random Forest Classifier**

### Final Model: **Random Forest**


## ⚙️ Performance Metrics

| Model         | Accuracy | 
| ------------- | -------------- | 
| SVM   | 98.48%          | 
| Random Forest     | 99.09%          | 

### Confusion Matrix & Report

* Evaluated using `classification_report` and `confusion_matrix`

---

## 🧪 Model Testing

* Created a prediction function to check custom inputs
* All test inputs passed through the same scaling as training
* Saved the model using `pickle`

---
## 🚀 How to Run
#### Clone the repository:
* `git clone https://github.com/yourusername/crop-recommendation.git`
* `cd crop-recommendation`
#### Install dependencies:
* `pip install -r requirements.txt`
#### Run prediction script or web app:
* `python crop_predictor.py`
#### or for Streamlit app
* `streamlit run app.py`

### 💡Future Improvements:

* Add weather API integration for live predictions
* Build mobile-friendly frontend using Streamlit
* Include soil health trends over time
* Generate alternate crop recommendations

---


## 👤 Author

**Nitya Chauhan**
Final Year Computer Engineering Student
Passionate about ML, Data Science, and building intelligent systems

---

## 📜 License

This project is under the MIT License.

---
