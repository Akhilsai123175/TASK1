# 🚢 Titanic Survival Prediction  
**Task 1 – Data Science Internship**

---

## 📖 Project Overview
The Titanic Survival Prediction project focuses on building a machine learning model to predict whether a passenger survived the Titanic disaster based on historical passenger data. This is a classic beginner-level data science project that helps understand data preprocessing, feature engineering, and classification algorithms.

In this project, a **Random Forest Classifier** is used to train and evaluate the model.

---

## 🎯 Objective
- Analyze passenger data from the Titanic dataset  
- Build a machine learning model to predict survival  
- Apply data preprocessing and supervised learning techniques  

---

## 📂 Project Structure
TASK1/
│
├── DATASET/
│ └── Titanic-Dataset.csv
│
├── MODEL/
│ └── app.py
│
├── README.md

---

## 📊 Dataset Description
The dataset includes the following features:

- **PassengerId** – Unique ID of the passenger  
- **Pclass** – Ticket class (1st, 2nd, 3rd)  
- **Sex** – Gender of the passenger  
- **Age** – Age of the passenger  
- **SibSp** – Number of siblings/spouses aboard  
- **Parch** – Number of parents/children aboard  
- **Fare** – Ticket fare  
- **Embarked** – Port of embarkation  
- **Survived** – Target variable (0 = Not Survived, 1 = Survived)

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- Scikit-learn  
- Random Forest Classifier  
- Git & GitHub  

---

## ⚙️ Model Workflow
1. Load the Titanic dataset  
2. Handle missing values (Age, Embarked)  
3. Encode categorical variables (Sex, Embarked)  
4. Drop unnecessary columns  
5. Split data into training and testing sets  
6. Train the Random Forest model  
7. Evaluate the model using accuracy and classification report  

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Akhilsai123175/TASK1.git

###2️⃣ Navigate to the project folder
cd TASK1

3️⃣ Install required libraries
pip install pandas scikit-learn

4️⃣ Run the model
python MODEL/app.py

