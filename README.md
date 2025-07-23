# 📉 Customer Churn Analysis and Prediction using Python

This project aims to analyze and predict customer churn using machine learning techniques. Customer churn refers to when customers stop using a company's product or service. Identifying churn patterns can help businesses take action to improve retention.

---

## 📊 Dataset

We use the **Telco Customer Churn** dataset which includes customer demographics, account information, and service usage.

- Source: Kaggle / Provide as a csv file 
- Target Variable: `Churn` (Yes/No)

---

## 🔧 Tools & Technologies

- Python 3.x
- Pandas
- NumPy
- Matplotlib / Seaborn (for visualization)
- Scikit-learn
- SMOTE (imbalanced-learn)

---

## 🧪 Project Workflow

### 1. **Data Preprocessing**
- Handle missing values
- Convert categorical variables using `LabelEncoder` or `OneHotEncoding`
- Normalize numerical features

### 2. **Exploratory Data Analysis (EDA)**
- Visualize churn distribution
- Analyze churn based on contract type, monthly charges, and tenure
- Correlation heatmap

### 3. **Handling Class Imbalance**
- Use SMOTE to oversample the minority class (`Churn = Yes`)

### 4. **Model Building**
- Model Used: `RandomForestClassifier`
- Split data into training and test sets (e.g., 70:30)
- Evaluate using accuracy, confusion matrix, precision, recall

### 5. **Model Evaluation**
- Accuracy score
- Confusion Matrix
- Classification Report

---

## 🚀 Results

- Achieved ~78% accuracy using Random Forest
- SMOTE significantly improved the model’s ability to detect churned customers

---

## 📌 Folder Structure

customer-churn-prediction/
│
├── data/
│ └── Telco-Customer-Churn.csv
│
├── notebook/
│ └── churn_analysis.ipynb
│
├── README.md
└── requirements.txt


---

## 🧠 Key Insights

- Customers with monthly contracts are more likely to churn
- High monthly charges increase churn risk
- Tenure is inversely related to churn probability

---

## 📦 Installation

```bash
pip install -r requirements.txt


