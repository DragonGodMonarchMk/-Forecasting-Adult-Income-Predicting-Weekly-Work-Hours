# -Forecasting-Adult-Income-Predicting-Weekly-Work-Hours
A dual-regression and classification machine learning project analyzing UCI Adult dataset to predict weekly work hours and forecast income level using advanced modeling and visualization techniques.
# 👨‍💼 Forecasting Adult Income & Predicting Weekly Work Hours

This project uses the **UCI Adult dataset** to tackle two related machine learning tasks:
1. **Regression**: Predict how many hours per week an adult works.
2. **Classification**: Predict whether an adult earns **more or less than $50K annually**.

Both tasks are approached with proper data preprocessing, visual analysis, model building, and performance evaluation.

## 🧠 Project Components

### 📘 Notebooks

- `the-prediction-of-hours-per-week-of-adult.ipynb`:  
  Regression modeling to predict `hours-per-week` based on demographic and occupational data.

- `forecasting-adult-income.ipynb`:  
  Classification modeling to predict `income` (`<=50K` or `>50K`).

## 📊 Dataset Details

- **File**: `adult11.csv`
- **Source**: [UCI Adult Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
- **Features**:
  - Age, Workclass, Education, Marital-status, Occupation, Relationship, Race, Sex, Capital-gain, Capital-loss, Hours-per-week, Native-country, Income
- **Target Variables**:
  - `hours-per-week` (regression)
  - `income` (classification)

## 🧪 Models Used

### Regression Notebook:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

### Classification Notebook:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- Support Vector Machine (SVM)

## 📈 Evaluation Metrics

- **Regression**:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score

- **Classification**:
  - Accuracy
  - Precision, Recall, F1-Score
  - Confusion Matrix
  - ROC-AUC Score

## 📉 Visualizations

- Correlation heatmaps
- Feature importance plots
- Confusion matrices
- ROC curves
- Distribution of work hours
- Income vs demographic variables


## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/adult-income-hours-prediction.git
   cd adult-income-hours-prediction
   jupyter notebook
pip install -r requirements.txt
pip install pandas numpy matplotlib seaborn scikit-learn



## 📁 File Structure

project/
│
├── the-prediction-of-hours-per-week-of-adult.ipynb
├── forecasting-adult-income.ipynb
├── adult11.csv
├── README.md
└── requirements.txt (optional)
