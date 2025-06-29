# 📉 Customer Churn Prediction

This project predicts whether a telecom customer will churn or stay, using supervised machine learning models. The notebook includes data preprocessing, visualization, model building, and evaluation. It is inspired by the Kaggle notebook: [Customer Churn Prediction by Bharti Prasad](https://www.kaggle.com/code/bhartiprasad17/customer-churn-prediction/notebook).

---

## 📂 Dataset

- **Source**: [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Records**: 7,043 customers
- **Features**:
  - **Demographics**: gender, SeniorCitizen, Partner, Dependents
  - **Services**: PhoneService, InternetService, StreamingTV, etc.
  - **Account Info**: tenure, MonthlyCharges, TotalCharges
  - **Target**: `Churn` (Yes/No)

---

## 🛠️ Tech Stack

- **Language**: Python 3
- **Libraries**:
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - scikit-learn
- **Environment**: Jupyter Notebook / Kaggle

---

## 🔍 Project Structure


---

## 📊 Steps Followed

### 1. Data Loading
- Loaded dataset using `pandas`
- Checked for missing/null values
- Converted `TotalCharges` from object to float

### 2. Exploratory Data Analysis (EDA)
- Plotted churn distribution
- Analyzed tenure, monthly charges, total charges
- Plotted correlations using heatmaps

### 3. Data Preprocessing
- Dropped unnecessary columns (`customerID`)
- Encoded binary features using Label Encoding
- Applied One-Hot Encoding to categorical variables

### 4. Model Building
- Trained two models:
  - Logistic Regression
  - Random Forest Classifier

### 5. Evaluation
- Used confusion matrix
- Evaluated with accuracy, precision, recall, F1-score

---

## ✅ Results

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| ~80%     |
| Random Forest      | ~85%     |

Random Forest showed better performance overall.

---

## ▶️ How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction.git
   cd customer-churn-prediction
## Install dependencies
pip install -r requirements.txt

## Run Jupyter Notebook
jupyter notebook


## Requirements
pandas
numpy
matplotlib
seaborn
scikit-learn
