# datafun-07-applied
CC7.1: Start a New Project (w/Local Project Virtual Env)


The purpose of this module is to develop a guided project. As the module progresses, additional topics will be covered, such as machine learning. Jupyter will be the tool used throughout the project.


 ## Project Setup

### 1️. Create and Activate Virtual Environment

Before running the scripts, set up a virtual environment:

#### Create virtual environment
python -m venv venv

#### Activate virtual environment (Windows)
venv\Scripts\activate

#### Activate virtual environment (Mac/Linux)

source venv/bin/activate

### Ensure your .gitignore includes:

.vscode/
.venv/
.ipynb_checkpoints/

### 2️. Install Required Dependencies

* Ensure all necessary libraries are installed:

pip install -r requirements.txt

### 3️. Ensure Jupyter is Installed

pip install jupyter


### 4️. Run Jupyter Notebook

jupyter notebook

### 5️. Verify Your Git Workflow

git status  # Check untracked changes
git add .   # Add all files
git commit -m "Initial project setup with virtual environment and requirements"
git push origin main  # Push changes to GitHub

### 6️. Double-Check GitHub

Open repository and verify all files are uploaded.