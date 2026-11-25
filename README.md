# House Price Exploratory Data Analysis (EDA)

A Python-based exploratory data analysis project that investigates a housing dataset to understand its structure, data quality, distributions, relationships, and the factors associated with house sale prices.

## Project Overview

The goal of this project is to explore the house-pricing data before any predictive modelling. The analysis is intended to help identify patterns, detect missing values and outliers, understand numerical and categorical features, and communicate findings through visualizations.

## Objectives

- Inspect the dataset structure, columns, and data types.
- Identify and handle missing or inconsistent values where appropriate.
- Explore distributions of important numerical features.
- Compare categorical features with house sale prices.
- Examine correlations and relationships between variables.
- Summarize observations using clear visualizations.

## Tools & Technologies

- Python
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Repository Structure

```text
House-Price-EDA-Project/
├── House_Price_EDA_Project_.ipynb   # Main analysis notebook (upload/commit this file)
├── train.csv                        # Source dataset (add the original dataset)
├── eda_dashboard.png                # EDA summary dashboard (add after generating from notebook)
├── requirements.txt                 # Python dependencies
└── README.md                        # Project documentation
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sahiljadhav3100-lab/House-Price-EDA-Project.git
cd House-Price-EDA-Project
```

### 2. Create and activate a virtual environment (recommended)

```bash
python -m venv .venv
```

Windows:
```bash
.venv\\Scripts\\activate
```

macOS / Linux:
```bash
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

Open `House_Price_EDA_Project_.ipynb` in Jupyter Notebook or Google Colab. Keep the original `train.csv` in the expected location or update the notebook's data-loading path.

## Dataset

Place the original training dataset at the repository root with the filename `train.csv`. The dataset file is not included yet; add the exact source CSV used in the notebook so that the analysis can be reproduced.

## Dashboard

The file `eda_dashboard.png` is reserved for a visual summary of the actual notebook findings. Generate it from the completed analysis and add it to this repository. Do not use illustrative or invented metrics in place of computed results.

## Reproducibility

1. Use the original dataset associated with the notebook.
2. Install the dependencies listed in `requirements.txt`.
3. Run the notebook cells from top to bottom.
4. Recreate and save the dashboard from the notebook's actual outputs.

## Author

**Sahil Jadhav**

---

If you use or extend this project, please retain attribution to the original dataset source and document any changes to the analysis.
