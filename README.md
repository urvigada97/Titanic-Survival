# Titanic Survival Prediction – MLOps Project

## Overview
This project is a machine learning pipeline to predict passenger survival on the Titanic using structured tabular data. It serves as a foundational exercise for learning key MLOps concepts such as reproducible project setup, data preprocessing, feature engineering, model training, and versioning.

## Objective
- Explore and analyze the Titanic dataset
- Handle missing data and engineer useful features
- Train a basic classification model
- Set up modular code and folder structure following MLOps best practices

## Project Structure
```
titanic-mlops/
│
├── data/                  # Raw and processed data
├── notebooks/             # Jupyter notebooks for exploration
├── src/                   # Reusable code modules
├── models/                # Saved model artifacts
├── reports/               # EDA results, charts
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
└── .gitignore             # Ignored files
```

## Technologies Used
- Python 3.10+
- Pandas, NumPy, Scikit-learn
- Seaborn, Matplotlib
- Jupyter Notebooks
- Git

## Setup Instructions
```bash
# Clone the repo
git clone https://github.com/your-username/titanic-mlops.git
cd titanic-mlops

# Set up virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
```

## Project Milestones
| Week   | Goal                                              |
| ------ | ------------------------------------------------- |
| Week 1 | EDA + Feature Engineering + Missing Data Handling |
| Week 2 | Model Training and Evaluation                     |
| Week 3 | Refactoring into reusable pipelines               |
| Week 4 | Deployment and CI/CD simulation                   |

## Resources Used
- [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
- [MLOps Zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp)
- [Hands-On ML Book (Aurélien Géron)](https://github.com/ageron/handson-ml)

## ✅ Current Status
✔️ Project initialized  
✔️ Data loaded and explored  
🛠️ Feature engineering in progress

## 📘 What You'll Learn
- Structuring ML projects for reproducibility
- Exploratory data analysis & missing value handling
- Preparing for scalable feature engineering
- Laying the foundation for CI/CD in ML
