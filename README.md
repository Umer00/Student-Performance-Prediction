# 🎓 Student Performance Prediction Using Machine Learning

### Analyzing Student Study Habits and Predicting Academic Performance with Python

## 📌 Project Overview

Student academic performance can be influenced by various factors, including study habits, previous academic scores, sleep duration, and exam preparation.

This project uses **Python and Machine Learning** to analyze student-related data and predict their academic performance based on these factors.

Using a dataset of 10,000 student records, the project explores relationships between study habits and academic outcomes through data analysis, visualization, and a Linear Regression model.

The goal is to demonstrate how data-driven techniques can help identify patterns in student performance and estimate a student's Performance Index.

## 🎯 Project Objectives

- Analyze student academic and study-related data.
- Explore relationships between study habits and performance.
- Perform exploratory data analysis (EDA).
- Visualize patterns using statistical charts.
- Prepare categorical data for machine learning.
- Build a Linear Regression model to predict the Performance Index.
- Evaluate model performance using R² Score and Mean Squared Error (MSE).

## 📂 Dataset Description

The project uses `Student_Performance.csv`, which contains **10,000 records and 6 columns**.

| Feature | Description |
|---|---|
| `Hours Studied` | Number of hours spent studying. |
| `Previous Scores` | Student's previous academic scores. |
| `Extracurricular Activities` | Whether the student participates in extracurricular activities. |
| `Sleep Hours` | Number of hours the student sleeps. |
| `Sample Question Papers Practiced` | Number of practice question papers completed. |
| `Performance Index` | Target variable representing the student's performance index. |

The dataset provides information about student study habits and academic performance, allowing the model to explore patterns between the input features and the target variable.

## ✨ Key Features

### 🔍 Exploratory Data Analysis
Inspect the dataset, examine its structure, and understand the distribution of student-related variables.

### 📊 Data Visualization
Use Matplotlib and Seaborn to visualize data distributions and relationships between features.

### 🧹 Data Preprocessing
Convert categorical extracurricular activity values into numerical representations suitable for model training.

### 🤖 Machine Learning
Implement a Linear Regression model to estimate the Performance Index from selected student-related features.

### 📈 Model Evaluation
Evaluate predictions using R² Score and Mean Squared Error to understand how closely the predictions match actual values.

## 🛠️ Technologies Used

- **Python** — Core programming language
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical data visualization
- **Scikit-learn** — Model training, data splitting, and evaluation
- **Jupyter Notebook / Google Colab** — Interactive development environment

## 🧠 Machine Learning Workflow

The project follows these main steps:

1. Load the student performance dataset.
2. Inspect the dataset and explore its features.
3. Analyze patterns and relationships in the data.
4. Convert categorical values into numerical form.
5. Select relevant input features and the target variable.
6. Split the data into training and testing sets.
7. Train a Linear Regression model.
8. Generate predictions on the test data.
9. Evaluate the predictions using R² Score and MSE.

## 📈 Model Evaluation

The notebook reports the following results for its Linear Regression model:

| Evaluation Metric | Result |
|---|---:|
| R² Score | 0.9887 |
| Mean Squared Error (MSE) | 4.1823 |

**R² Score:** Measures how well the model explains the variation in the target variable. A score closer to 1 generally indicates a better fit.

**Mean Squared Error:** Measures the average squared difference between actual and predicted values. Lower values generally indicate smaller prediction errors.

These results reflect the evaluation output recorded in the notebook. They should be interpreted in the context of the dataset, feature selection, and train-test setup.

## 📁 Repository Structure

```text
Student-Performance-Prediction/
│
├── Student_Performance.csv
│   └── Dataset containing 10,000 student records
│
├── Student_Performance_Prediction.ipynb
│   └── Data analysis, visualization, model training,
│       prediction, and evaluation
│
├── README.md
│   └── Project documentation
│
└── LICENSE
    └── MIT License
```

## 🚀 Getting Started

Follow these steps to run the project on your local machine.

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab
- Git (optional)

### Step 1: Clone the Repository

```bash
git clone https://github.com/Umer00/Student-Performance-Prediction.git
```

### Step 2: Navigate to the Project Folder

```bash
cd Student-Performance-Prediction
```

### Step 3: Install the Required Libraries

```bash
python -m pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open and Run the Notebook

Open `Student_Performance_Prediction.ipynb` and execute the cells sequentially.

**Note:** Keep `Student_Performance.csv` in the project directory so the notebook can load the dataset using its relative file path.

Alternatively, you can open the notebook in Google Colab and upload the CSV file when required.

## 💡 Learning Outcomes

This project provides practical experience in:

- Data analysis using Pandas and NumPy
- Exploratory Data Analysis (EDA)
- Statistical data visualization
- Categorical data encoding
- Feature selection
- Training a regression model
- Making predictions using Scikit-learn
- Evaluating machine learning models
- Understanding regression evaluation metrics

## 🔮 Future Improvements

The project could be extended by:

- Comparing Linear Regression with Random Forest and other regression algorithms.
- Using cross-validation for more reliable model evaluation.
- Analyzing feature importance and correlations.
- Creating actual-versus-predicted visualizations.
- Investigating prediction errors and possible data leakage.
- Developing an interactive application for student performance prediction.

## 📜 License

This project is licensed under the MIT License. Refer to the `LICENSE` file for details.

---

**Built with Python, Data Analysis, and Machine Learning.**
