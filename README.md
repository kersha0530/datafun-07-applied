# datafun-07-applied
CC7.1: Start a New Project (w/Local Project Virtual Env)

# 📊 NYC January High Temperature Prediction  
## Author: Kersha  Broussard
## Github Repo Link: https://github.com/kersha0530/datafun-07-applied
## **🔍 Overview**  
This project analyzes historical **NYC January high temperatures** from **1895 to 2018** and uses **linear regression** to predict future temperatures.  

Two approaches were used:  
1️. **SciPy’s `linregress()`** for quick regression analysis  
2️. **Scikit-Learn’s `LinearRegression()`** with train/test splits for improved accuracy  

## **📂 Project Structure**

datafun-07-applied/ 
│── chapter_10_examples/ # Raw dataset files
│── chapter_15_examples/ # ML-focused case studies 
│── notebooks/ # Jupyter Notebooks │ 
├── kersha_ml.ipynb # Main project notebook 
│── README.md # Project documentation 
│── requirements.txt # Project dependencies 
│── .gitignore # Ignore unnecessary files

 ## Project Setup
 
---

## **📦 Dependencies**
Ensure you have the following Python packages installed:

```txt
numpy
pandas
matplotlib
seaborn
scipy
scikit-learn

OR install all required packages using:

```bash

pip install -r requirements.txt
```

### 1️. Create and Activate Virtual Environment

Before running the scripts, set up a virtual environment:

#### * Create virtual environment
python -m venv venv

#### * Activate virtual environment (Windows)
venv\Scripts\activate

#### * Activate virtual environment (Mac/Linux)

source venv/bin/activate

### * Ensure your .gitignore includes:

- .vscode/
- .venv/
- .ipynb_checkpoints/

### 2️. Install Required Dependencies

* Ensure all necessary libraries are installed:

pip install -r requirements.txt

### 3️. Ensure Jupyter is Installed

pip install jupyter


### 4️. Run Jupyter Notebook

jupyter notebook

### 5️. Verify Your Git Workflow

- git status  # Check untracked changes
- git add .   # Add all files
- git commit -m "Initial project setup with virtual environment and requirements"
- git push origin main  # Push changes to GitHub

### 6️. Double-Check GitHub

Open repository and verify all files are uploaded.


# Project Breakdown

### 1️. Data Preparation
* Load NYC temperature dataset (ave_hi_nyc_jan_1895-2018.csv)
* Clean and preprocess data (rename columns, convert date formats)
### 2️. Exploratory Data Analysis
* Describe dataset statistics
* Visualize trends with Seaborn
### 3️. Linear Regression (SciPy)
* Use linregress() to compute the best-fit line
* Predict 2024 temperature manually using y = mx + b
### 4️. Machine Learning (Scikit-Learn)
* Split dataset into training & testing
* Train LinearRegression() model
* Evaluate model performance
* Predict 2024 temperature
### 5️. Results & Visualizations
* Scatter plots with regression lines
* Insights comparing SciPy & Scikit-Learn results

