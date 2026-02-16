# datafun-06-eda
Foundations of Data Analytics, Module 6. Custom EDA Project.

**Author:** Grace Tulsi  
**Date:** February 2026  
**Purpose:** Perform exploratory data analysis (EDA) on a dataset using Jupyter, pandas, and Seaborn.
**Dataset:** Students Performance in Exams  
**Source:** [Kaggle - Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

## Initial Setup
1. Created this repo on GitHub with a default README.
2. Opened the Repos folder from the C drive in Windows PowerShell and used git clone to clone it to my machine.
3. Used cd datafun-06-eda in PowerShell, then code . to open the project in VS Code.
4. Added .gitignore and requirements.txt with contents from pro-analytics-01.
5. Git add, commit, and push to GitHub.
6. Enabled GitHub Actions in repo Settings > Pages.
7. Enabled Dependabot security updates in repo Settings > Advanced Security.

## Virtual Environment Setup
8. Had to reinstall Python 3.14.3 from python.org (checked Add to PATH).
9. Created the project virtual environment with py -m venv .venv.
10. Activated the virtual environment with .venv\Scripts\Activate.
11. Installed project dependencies with py -m pip install jupyterlab pandas pyarrow matplotlib seaborn.
12. Upgraded pip, setuptools, and wheel with py -m pip install --upgrade pip setuptools wheel.
13. Installed all requirements.txt dependencies with py -m pip install --upgrade -r requirements.txt.
14. Created gracetulsi_eda.ipynb notebook in the root project folder.
15. Added Markdown introduction cell with title, author, date, and purpose.
16. Added Python cell with import statements for matplotlib, pandas, and seaborn.
17. Downloaded Students Performance in Exams dataset from Kaggle.
18. Created data/raw/ and data/processed/ folders.
19. Added StudentsPerformance.csv to data/raw/.

## Reminder
Activate the virtual environment every time you open a new terminal:
```shell
.venv\Scripts\Activate
```

## Commands Used
```shell
git clone https://github.com/gracetulsi/datafun-06-eda
cd datafun-06-eda
code .
git add .
git commit -m "Add .gitignore, requirements.txt, and update README"
git push -u origin main
py -m venv .venv
.venv\Scripts\Activate
py -m pip install jupyterlab pandas pyarrow matplotlib seaborn
py -m pip install --upgrade pip setuptools wheel
py -m pip install --upgrade -r requirements.txt
```