# DATATHON 2026 — The Gridbreakers

Machine Learning project for forecasting sales revenue using historical e-commerce data.

---

# 📌 Project Overview

This repository contains experiments and forecasting models developed for the DATATHON 2026 competition.

Main objectives:

* Analyze historical sales data
* Build forecasting models for revenue prediction
* Compare baseline and advanced approaches
* Visualize trends and model performance
* Generate final prediction results

---

# 📂 Project Structure

```bash
DATATHON-2026---The-Gridbreakers/
│
├── baseline.ipynb
│   └── Baseline forecasting model
│
├── multiple.ipynb
│   └── Multiple model experiments & comparisons
│
├── revenue_forecasting.ipynb
│   └── Main notebook for training and forecasting revenue
│
├── visualize.ipynb
│   └── Data visualization and exploratory analysis (EDA)
│
├── .gitignore
│   └── Ignore unnecessary files when pushing to GitHub
│
└── README.md
    └── Project documentation
```

---

# ⚙️ Requirements

Install Python packages before running the notebooks.

Recommended Python version:

```bash
Python 3.10+
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost lightgbm jupyter
```

Or using requirements.txt:

```bash
pip install -r requirements.txt
```

---

# 🚀 How To Run

## 1. Clone Repository

```bash
git clone https://github.com/vyvy31082004/DATATHON-2026---The-Gridbreakers.git
```

## 2. Move Into Project Folder

```bash
cd DATATHON-2026---The-Gridbreakers
```

---

# ▶️ Run Jupyter Notebook

Start Jupyter:

```bash
jupyter notebook
```

Then open notebooks in this order:

| Notebook                    | Purpose                    |
| --------------------------- | -------------------------- |
| `visualize.ipynb`           | Exploratory Data Analysis  |
| `baseline.ipynb`            | Baseline model             |
| `multiple.ipynb`            | Compare multiple models    |
| `revenue_forecasting.ipynb` | Final forecasting pipeline |

---

# 📊 Workflow

```text
Raw Data
   ↓
Data Cleaning
   ↓
Feature Engineering
   ↓
Visualization
   ↓
Model Training
   ↓
Forecasting
   ↓
Evaluation
```

---

# 🧠 Models Used

Possible models used in this project:

* Linear Regression
* Random Forest
* XGBoost
* LightGBM
* Time-Series Forecasting

Evaluation metrics:

* MAE
* RMSE
* MAPE

---

# 📈 Features

* Revenue forecasting
* Data visualization
* Feature engineering
* Model comparison
* Time-series analysis

---

# 🛠 Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

---

# 👥 Team

Team Name: **The Gridbreakers**

---

# 📌 Notes

* Make sure dataset files are placed in the correct directory before running notebooks.
* Large datasets are ignored using `.gitignore`.
* Run notebooks sequentially to avoid missing variables or processed data.

---

# 📄 License

This project is for educational and competition purposes only.
