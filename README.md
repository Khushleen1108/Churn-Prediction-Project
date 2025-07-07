# 📉 Customer Churn Prediction (Telecom)

Welcome to the **Churn Prediction** project repository! This project aims to analyze telecom customer data to predict whether a customer is likely to **churn (leave the service)** using machine learning techniques. By accurately identifying customers at risk, telecom companies can take proactive steps to improve customer retention. 

---

## 📁 Repository Structure

| File / Folder                             | Description                                                     |
|-------------------------------------------|-----------------------------------------------------------------|
| 📄 `Churn Prediction DFD.pdf`             | Data Flow Diagram showing the preprocessing and modeling steps |
| 📄 `Churn Prediction Project Report.pdf`  | Detailed project report with methodology and findings           |
| 📊 `Churn Prediction Project ppt.pptx`    | PowerPoint presentation summarizing key aspects of the project |
| 📄 `Churn Requirement Analysis.pdf`       | Document outlining the project's functional requirements        |
| 📓 `Churn prediction.ipynb`               | Main Jupyter Notebook with code implementation                 |
| 📋 `churn.csv`                            | Dataset used for training and evaluation                        |
| 📄 `LICENSE`                              | License file (MIT License)                                      |
| 📘 `README.md`                            | Project overview, setup instructions, and documentation         |
| 📦 `requirements.txt`                     | List of required Python libraries and dependencies              |

---

## 🔍 Project Description

Customer churn refers to the phenomenon where users stop using a company's service. In the telecom sector, understanding and predicting churn is essential as acquiring new customers is more costly than retaining existing ones.

This project uses supervised machine learning algorithms to:
- Analyze customer behavior
- Predict whether a customer will churn
- Interpret the most influential factors affecting churn

---

---

## 🚀 Key Features

- 🧹 **Data Preprocessing**:
  - Handling missing values
  - Encoding categorical variables
  - Feature scaling (MinMax Scaling)

- 📊 **Exploratory Data Analysis (EDA)**:
  - Correlation analysis
  - Count plots and feature distributions

- 🤖 **Machine Learning Models**:
  - Logistic Regression
  - Random Forest
  - Decision Tree
  - Support Vector Machine (SVM)
  - AdaBoost
  - XGBoost

- 🔍 **Model Evaluation**:
  - Accuracy, Precision, Recall, F1 Score
  - Classification Report

- 🧪 **Hyperparameter Tuning**:
  - GridSearchCV to optimize model performance

- 🏆 **Best Performing Model**:
  - **XGBoost** was found to be the most effective based on evaluation metrics

- 📉 **Model Interpretability with SHAP**:
  - Visualizes feature importance using SHAP values
  - Explains how individual features impact the model’s output
  - Helps stakeholders understand and trust the predictions
---

## 📦 Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/Khushleen1108/Churn-Prediction.git
cd Churn-Prediction
```

2. Create a virtual environment (optional but recommended):
```
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Open the notebook:

```
jupyter notebook Churn\ prediction.ipynb
```

---

## 🧪 Dataset

- 📂 Source: [Kaggle - Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- 🧾 Rows: 7043 customers
- 📊 Columns: 21 features including:
  - Demographics (e.g., gender, senior citizen, tenure)
  - Services (e.g., Internet service, phone service, etc.)
  - Contract details and billing
  - Churn indicator (Yes/No)

---

## 📄 License
This project is licensed under the MIT License.


## 📬 Contact
For any questions or feedback, please contact Khushleen Kaur at k2aur8154@gmail.com.

