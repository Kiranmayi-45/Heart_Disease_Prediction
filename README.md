# 🫀 Heart Disease Risk Prediction System

This project presents a **machine learning-based application** designed to predict the risk of heart disease using multiple classification algorithms. By leveraging clinical data and a user-friendly graphical interface, the system aims to provide quick and reliable health risk assessments to support informed decision-making.

---

## 🎯 Objective

The goal of this project is to **assess an individual's risk of heart disease** by analyzing key health metrics using **supervised machine learning techniques**. The system offers predictions from multiple models to enhance the reliability and interpretability of the results.

---

## 📊 Machine Learning Models Used

The following models were trained and evaluated on the **UCI Heart Disease Dataset** using appropriate preprocessing techniques such as feature scaling and train-test split:

| Model                 | Accuracy  |
|----------------------|-----------|
| K-Nearest Neighbors  | 90.16%    |
| Decision Tree        | 75.41%    |
| Random Forest        | 83.61%    |

---

## 💻 Application Features

- **Multi-Model Prediction**: Offers predictions from KNN, Decision Tree, and Random Forest classifiers for comparative analysis.
- **User-Friendly GUI**: Built with **Tkinter**, the application allows users to input personal health data through an intuitive graphical interface.
- **Real-Time Predictions**: Instantly displays predictions from all three models once input is submitted.
- **Clinical Feature Support**: Uses essential clinical parameters, including:
  - Age
  - Sex
  - Chest Pain Type (`cp`)
  - Resting Blood Pressure (`trestbps`)
  - Serum Cholesterol (`chol`)
  - Fasting Blood Sugar (`fbs`)
  - Resting ECG (`restecg`)
  - Maximum Heart Rate Achieved (`thalach`)
  - Exercise-Induced Angina (`exang`)
  - ST Depression (`oldpeak`)
  - Slope of the Peak Exercise ST Segment (`slope`)
  - Number of Major Vessels Colored by Fluoroscopy (`ca`)
  - Thalassemia (`thal`)

---

## 🛠 Tech Stack

- **Language**: Python  
- **Libraries**: `scikit-learn`, `pandas`, `numpy`, `tkinter`  
- **IDE**: Jupyter Notebook  
- **Dataset**: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease)

---

## 📌 Conclusion

This project demonstrates the practical application of machine learning in healthcare. By combining multiple high-performing models with a responsive and intuitive interface, the system empowers users to gain insights into their heart health and make more informed decisions. The integration of accessible technology with predictive analytics highlights the potential of AI in preventive medicine.

---




