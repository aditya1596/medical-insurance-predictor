# Medical Insurance Premium Predictor 💰

An end-to-end machine learning project to predict medical insurance charges based on user attributes like age, BMI, smoking habits, and region.

---

## 📊 Project Overview

Developed a predictive model using 1.3K+ insurance records to estimate medical insurance costs. The project covers the complete ML lifecycle including data preprocessing, model training, evaluation, and deployment using Flask.

---

## 🧠 Key Features

* Predict insurance premium based on user inputs
* Multiple ML models implemented and compared
* Deployed using Flask web application
* Dockerized for easy deployment

---

## ⚙️ Technologies Used

* **Python** – Data processing and model building
* **Scikit-learn** – Regression models
* **Pandas, NumPy** – Data handling
* **Matplotlib, Seaborn** – Visualization
* **Flask** – Web application deployment
* **Docker** – Containerization

---

## 🔧 ML Workflow

* Data cleaning and preprocessing
* Feature encoding (categorical variables)
* Model training using:

  * Linear Regression
  * Decision Tree
  * Random Forest
  * Gradient Boosting (Best)
* Model evaluation using MAE, RMSE, and R²

---

## 📈 Results

* Achieved best performance using Gradient Boosting Regressor
* R² Score: ~0.85+
* Improved prediction accuracy through feature scaling and tuning

---

## 🚀 Deployment

* Built a Flask-based web app (`app.py`) for user interaction
* Users can input details and get predicted insurance cost
* Dockerized application for scalable deployment

---

## 📁 Project Structure

```id="mlproj1"
├── app.py
├── Medical_Insurance_Premium.ipynb
├── MIPML.pkl
├── insurance.csv
├── Dockerfile
├── requirements.txt
└── templates/
```

---

## 🎯 Key Insights

* Smoking significantly increases insurance cost (~2–3x higher)
* Higher BMI correlates with increased medical expenses
* Age is a strong predictor of insurance premium

---

## 📞 Contact

**Aditya Singh Shekhawat**

* GitHub: https://github.com/aditya1596
* LinkedIn: https://www.linkedin.com/in/aditya-singh-shekhawat-934930288/

---

 If you found this project useful, give it a star!
