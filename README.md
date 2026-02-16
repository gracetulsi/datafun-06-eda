# datafun-06-eda
Foundations of Data Analytics, Module 6. Custom EDA Project.

**Author:** Grace Tulsi  
**Date:** February 2026  
**Purpose:** Perform exploratory data analysis (EDA) on a dataset using Jupyter, pandas, and Seaborn.

## Dataset Description

**Dataset:** Students Performance in Exams  
**Source:** [Kaggle - Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)  
**Records:** 1,000

| Column | Description | Type |
|--------|-------------|------|
| gender | Male or female | Categorical |
| race/ethnicity | Student group (A, B, C, D, E) | Categorical |
| parental level of education | Highest education level of parent | Categorical |
| lunch | Standard or free/reduced program | Categorical |
| test preparation course | Completed or none | Categorical |
| math score | Math exam score (0-100) | Numeric |
| reading score | Reading exam score (0-100) | Numeric |
| writing score | Writing exam score (0-100) | Numeric |

## Initial Setup
1. Created this repo on GitHub with a default README.
2. Opened the Repos folder from the C drive in Windows PowerShell and used git clone to clone it to my machine.
3. Used cd datafun-06-eda in PowerShell, then code . to open the project in VS Code.
4. Added .gitignore with contents from datafun-04-notebooks.
5. Added pyproject.toml with project dependencies for uv workflow.
6. Git add, commit, and push to GitHub.
7. Enabled GitHub Actions in repo Settings > Pages.
8. Enabled Dependabot security updates in repo Settings > Advanced Security.

## Virtual Environment Setup
9. Created the project virtual environment and installed all dependencies using uv:
```shell
uv self update
uv python pin 3.14
uv sync --extra dev --extra docs --upgrade
```
10. Verified the new .venv folder appeared in the root project folder.
11. Created gracetulsi_eda.ipynb notebook in the root project folder.
12. Selected the .venv kernel in the Jupyter notebook (top right > Select Kernel > datafun-06-eda).
13. Added Markdown introduction cell with title, author, date, and purpose.
14. Added Python cell with import statements for matplotlib, pandas, and seaborn.
15. Downloaded Students Performance in Exams dataset from Kaggle.
16. Created data/raw/ and data/processed/ folders.
17. Added StudentsPerformance.csv to data/raw/.

## Commands Used
```shell
git clone https://github.com/gracetulsi/datafun-06-eda
cd datafun-06-eda
code .
uv self update
uv python pin 3.14
uv sync --extra dev --extra docs --upgrade
git add .
git commit -m "descriptive message"
git push -u origin main
```