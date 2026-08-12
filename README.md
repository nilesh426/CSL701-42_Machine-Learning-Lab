# CSL701-42_Machine-Learning-Lab

Machine Learning Lab Experiments for Semester 7 Computer Engineering.

## Overview
This repository contains Jupyter Notebook lab experiments created for the Machine Learning lab (CSL701) — by Nilesh Ashok Sawant (Roll: CE42). The notebooks demonstrate basic data loading, exploratory data analysis (EDA), visualization, data cleaning, and simple modelling (OLS regression) on small public datasets.

## Contents
- Experiments/
  - ML_EXP1.ipynb — Titanic dataset: EDA, cleaning, visualizations, basic statistics.
  - ML_Exp2.ipynb — Auto MPG dataset: data cleaning, EDA, simple linear regression (OLS) predicting MPG from horsepower.
- README.md — this file

## Notebooks (quick links)
- Experiments/ML_EXP1.ipynb — Open in Colab: https://colab.research.google.com/github/nilesh426/CSL701-42_Machine-Learning-Lab/blob/main/Experiments/ML_EXP1.ipynb
- Experiments/ML_Exp2.ipynb — Open in Colab: https://colab.research.google.com/github/nilesh426/CSL701-42_Machine-Learning-Lab/blob/main/Experiments/ML_Exp2.ipynb

## Requirements
The notebooks are written for Python 3 and use the following libraries (typical for data-science environments):
- pandas
- numpy
- matplotlib
- seaborn

They run directly in Google Colab (no local setup required) or in a local Jupyter environment with the above packages installed.

## How to run
Option A — Google Colab (recommended):
1. Click one of the "Open in Colab" links above.
2. When prompted, upload the dataset file(s) used by the notebook:
   - ML_EXP1.ipynb expects a Titanic dataset (the notebook uses a file named `Titanic-Dataset.csv`).
   - ML_Exp2.ipynb expects an Auto MPG dataset (example filename used in the notebook: `auto-mpg (1).csv`).
3. Run the notebook cells (Runtime -> Run all).

Option B — Locally with Jupyter:
1. Clone this repository:

   git clone https://github.com/nilesh426/CSL701-42_Machine-Learning-Lab.git
   cd CSL701-42_Machine-Learning-Lab

2. Create and activate a virtual environment (optional but recommended):

   python3 -m venv .venv
   source .venv/bin/activate  # macOS / Linux
   .venv\Scripts\activate     # Windows (PowerShell)

3. Install dependencies:

   pip install pandas numpy matplotlib seaborn jupyter

4. Start Jupyter and open the notebooks:

   jupyter notebook

5. Upload the required dataset files into the notebook session (same filenames as used in the notebooks), then run the cells.

## Notes and suggestions
- The notebooks were authored in Google Colab and include Colab-specific upload helpers; they work well in Colab where the upload UI is available.
- The datasets are not stored in the repository. If you want the notebooks to run without manual uploads, add the dataset files to the Experiments/ directory and update the notebook paths accordingly.
- Consider adding a requirements.txt or environment.yml if you want reproducible local environments.

## Attribution
Author: Nilesh Ashok Sawant (Roll: CE42)

---

If you'd like, I can:
- add a requirements.txt,
- add the datasets to the repo (if you provide them), or
- convert the notebooks into polished reports or Python scripts.
