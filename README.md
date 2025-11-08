# ml_classification_blessing
#  Midterm Project: Classification Analysis (Titanic Survival)

**Author:** Blessing Aganaga  
**Date:** November 2025  
**Course:** Module 4 – Applied Machine Learning  

---

## 📘 Project Overview

This project applies machine learning classification techniques to predict **Titanic passenger survival** based on demographic and ticket information.  
The project demonstrates key ML workflow skills:
- Data cleaning and preprocessing  
- Feature encoding and scaling  
- Model training, evaluation, and comparison  
- Performance visualization (ROC, PR curves)

---

## 📊 Dataset

**Dataset Used:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)  
- **Target Variable:** `Survived` (0 = No, 1 = Yes)  
- **Features:** Age, Sex, Passenger Class, Fare, Embarked, etc.  
- Data file: `data/titanic.csv`

---

## Notebook

**Notebook file:**  
[classification_blessing.ipynb](./notebooks/classification_blessing.ipynb)

This notebook follows the required structure:
1. Import and Inspect the Data  
2. Data Exploration and Preparation  
3. Feature Selection and Justification  
4. Model Training and Evaluation  
5. Model Improvement and Comparison  
6. Final Thoughts and Insights  

---



## Environment Setup

To run this project locally:
```bash
# Clone the repository
git clone https://github.com/teflxndxn/ml_classification_blessing.git
cd ml_classification_blessing

# Create virtual environment
python -m venv .venv
source .venv/bin/activate   # Mac
# .venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter lab
