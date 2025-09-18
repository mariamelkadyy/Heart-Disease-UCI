# Heart Disease Prediction - UCI Dataset

## 📌 Project Overview
This project analyzes and predicts the risk of heart disease using the **UCI Heart Disease dataset**.  
It includes preprocessing, feature selection, supervised and unsupervised models, and a Streamlit app for predictions.  
The project was completed as part of a Machine Learning graduation project.

---

## 🚀 Features
- Data Preprocessing & Cleaning
- Dimensionality Reduction (PCA)
- Feature Selection (RFE, Chi-Square, Feature Importance)
- Supervised Models: Logistic Regression, Decision Tree, Random Forest, SVM
- Unsupervised Models: K-Means, Hierarchical Clustering
- Hyperparameter Tuning with GridSearchCV/RandomizedSearchCV
- Streamlit Web App for user interaction
- Deployment using Ngrok (for public sharing)

---

## 📂 Repository Structure
Heart_Disease_Project/
│── data/
│ ├── heart_disease.csv
│── notebooks/
│ ├── Heart Disease UCI.ipynb
│── models/
│ ├── final_model.pkl
│── ui/
│ ├── app.py
│── deployment/
│ ├── ngrok_setup.txt
│── results/
│ ├── evaluation_metrics.txt
│── README.md
│── requirements.txt

## ⚙️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Heart_Disease_Project.git
   cd Heart_Disease_Project

Install dependencies:
pip install -r requirements.txt

▶️ Usage
Run Jupyter Notebook
jupyter notebook

Run Streamlit App
streamlit run ui/app.py

📊 Dataset
The dataset used is the UCI Heart Disease Dataset.

👩‍💻 Author
Mariam Elkady
