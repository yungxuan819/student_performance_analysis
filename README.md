# 📚 Student Performance Analysis

A data analysis and machine learning project that explores how factors like **parental education, lunch type, and test preparation** influence students' academic scores — and builds predictive models to estimate student performance.

---

## 📁 Project Structure

```
student_performance_analysis/
│
├── StudentsPerformance.ipynb   # Main notebook: EDA, visualizations & prediction models
└── StudentsPerformance.csv     # Dataset: 1,000 students with demographic & score data
```

---

## 📊 Dataset

The dataset contains records for **1,000 students** with the following features:

| Column | Description |
|--------|-------------|
| `gender` | Student's gender |
| `race/ethnicity` | Student's ethnic group |
| `parental level of education` | Highest education level of the parent |
| `lunch` | Standard or free/reduced lunch |
| `test preparation course` | Whether the student completed a prep course |
| `math score` | Math exam score (0–100) |
| `reading score` | Reading exam score (0–100) |
| `writing score` | Writing exam score (0–100) |

Source: [Students Performance in Exams — Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

---

## 🔍 Project Overview

### Exploratory Data Analysis (EDA)
- Distribution of scores across math, reading, and writing
- Impact of parental education level on student scores
- Effect of test preparation course completion on performance
- Score breakdowns by gender and lunch type

### Prediction Models
- Regression models trained to predict student scores based on demographic and background features
- Model evaluation using standard metrics (e.g. MAE, RMSE, R²)

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook

### Installation

```bash
git clone https://github.com/yungxuan819/student_performance_analysis.git
cd student_performance_analysis
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Run

```bash
jupyter notebook StudentsPerformance.ipynb
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| pandas | Data loading & manipulation |
| matplotlib / seaborn | Data visualization |
| scikit-learn | Machine learning models |
| Jupyter Notebook | Development environment |
