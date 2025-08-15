# **AAIML FINAL EXAM PART B**

Welcome to my FINAL EXAM PART B.

This repo contains:

### - The Jupyter Notebook
The notebook `8963215_AAIML_FinalExamPartB.ipynb` implementing:

- Data loading from OneDrive and conversion from CSV to Parquet for efficiency.
- Filtering from the original dataset (~67M rows) to 1M rows for faster processing.
- Data preprocessing:
  - Handling missing values.
  - Feature engineering at user level (views, sessions, average price, total spent, purchases, recency, favorite category).
- Exploratory Data Analysis (EDA):
  - Top categories.
  - Event type distribution.
  - Price distributions and outliers.
  - Feature correlation heatmap.
- Feature scaling and dimensionality reduction with **PCA** (6 components, 95% variance explained).
- **K-Means clustering** with Elbow and Silhouette methods for K selection.
- Cluster profiling with radar and line charts.
- Automated marketing insights per cluster.

### HTML Export (for GitHub Pages)
You can view the published notebook [here](https://paulamrz-c.github.io/CSCN8000-Final-Exam-PR/8963215_AAIML_FInalExamPartB.html)

## Quick Start

```bash
python -m venv venv
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
.\venv\Scripts\activate
pip install -r requirements.txt
python -m ipykernel install --user --name=venv --display-name "Python PR (venv)"
jupyter notebook
```

### 🐍 Python Installation (if not already installed)

This project requires **Python 3.10 or higher**.

To check if Python is installed, open PowerShell and run:

```powershell
python --version
```

If you get a message saying that Python is not recognized, you can download and install it directly using the following commands:

```powershell
curl -o python-installer.exe https://www.python.org/ftp/python/3.12.3/python-3.12.3-amd64.exe
Start-Process python-installer.exe
```

This will download the official Python installer and launch it.
➡️ Make sure to check the option “Add Python to PATH” during installation.

Once installed, reopen PowerShell and verify:

```powershell
python --version
```

## Data Sources

- E-Commerce Transactions Dataset – Olist (via Kaggle)
