# LogiClassify: Logistic Regression Classification Project

## 📌 Overview
LogiClassify is a simple and beginner-friendly Machine Learning project that demonstrates how Logistic Regression can be used to classify data.  
The project includes:
- Loading a dataset using pandas  
- Exploratory Data Display  
- Training a Logistic Regression model  
- Making predictions  
- Evaluating performance with Accuracy Score  
- Plotting a Confusion Matrix  

This project is perfect for students, lab exams, or anyone learning basic ML.

---

## 📂 Project Structure
|-- dataset.csv : 
|-- main.py
|-- README.md


---

## 🚀 Steps Performed

### 1️⃣ Import Required Libraries
- pandas  
- numpy  
- sklearn (model, train-test split, metrics)

### 2️⃣ Load & Display Dataset
The dataset is read using `pandas.read_csv()` and displayed as a dataframe.

### 3️⃣ Preprocess Data
- Separate features (X) and target (y)
- Train-test split (80% training, 20% testing)

### 4️⃣ Train Logistic Regression Model
```python
from sklearn.linear_model import LogisticRegression
model = LogisticRegression()
model.fit(X_train, y_train)
