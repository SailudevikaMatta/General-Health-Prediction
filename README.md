# ❤️ Cardiovascular Disease Prediction using Machine Learning

## 📌 Overview

This project focuses on predicting the presence of cardiovascular (heart) disease using Machine Learning techniques. It involves data preprocessing, model training, evaluation, and performance comparison across multiple algorithms.

The goal is to build an efficient and interpretable model that can assist in early detection of heart disease based on patient health data.

---

## 🚀 Features

* 📊 Data preprocessing and cleaning
* 🔢 Encoding categorical variables
* 🤖 Training multiple ML models:

  * Support Vector Machine (SVM)
  * Random Forest Classifier
  * Logistic Regression
* 📈 Model evaluation using:

  * Accuracy Score
  * Classification Report
  * Confusion Matrix
* 📉 Visualization of model performance
* ⚙️ Hyperparameter tuning using RandomizedSearchCV

---

## 🧠 Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## 📂 Project Structure

```
project/
│── data/
│    └── sample_data.csv
│
│── notebook.ipynb        # Step-by-step experimentation
│── main.py              # Final clean implementation
│── README.md
│── requirements.txt
```

---

## 📊 Dataset

The dataset used contains patient health-related information such as age, blood pressure, cholesterol levels, and lifestyle habits.

🔗 **Dataset Download**:
You can download the dataset from:

* Google Drive / Kaggle (add your link here)

📌 After downloading, place the dataset in:

```
data/CVD_cleaned.csv
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Install dependencies

```
pip install -r requirements.txt
```

### 3️⃣ Add dataset

* Download dataset from the link above
* Place it inside the `data/` folder

---

## ▶️ How to Run

### Run the main script:

```
python main.py
```

### Or open the notebook:

```
notebook.ipynb
```

---

## 📈 Model Performance

The project compares multiple models based on accuracy and other evaluation metrics:

* ✔ Support Vector Machine
* ✔ Random Forest
* ✔ Logistic Regression

A bar chart visualization is used to compare model performance.

---

## 🔧 Hyperparameter Tuning

Random Forest model is further optimized using:

* RandomizedSearchCV
* Cross-validation

This improves model performance and helps find the best parameters.

---

## 📌 Results

* Achieved reliable predictions across multiple models
* Random Forest generally performs better after tuning
* Visualization helps in easy comparison

---

## 🎯 Future Improvements

* Add more advanced models (XGBoost, Neural Networks)
* Deploy as a web application
* Improve feature engineering
* Use larger and more diverse datasets

---

## 👩‍💻 Author

**Devika Matta**
Student | Machine Learning Enthusiast

---

## ⭐ Acknowledgements

* Scikit-learn documentation
* Open datasets from Kaggle
* Machine Learning community

---

## 📢 Note

If the dataset is not present, the project uses a sample dataset for demonstration.
Ensure the correct dataset is placed in the `/data` folder for full functionality.

---

⭐ *If you like this project, consider giving it a star!*
