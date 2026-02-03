# Adult Census Income Dataset: EDA & ML

## About

This repo is my place to explore the Adult Census Income dataset (also called the “Adult Income” dataset). It’s a classic dataset about demographic and work‑related features with a target label for income. If you are new to data work, that’s totally fine — the notebooks are meant to be opened and followed step by step.

## What’s inside

```
.
├── data/
│   ├── Adult_income.csv
│   └── adult.csv
├── notebooks/
│   ├── Adult_Income_EDA.ipynb
│   └── Adult_Income_Machine_Learning.ipynb
└── README.md
```

## How to use this (simple steps)

1. **Create a virtual environment (optional)**  
   If you’ve never used one, you can skip this step.

   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```

2. **Install dependencies**

   ```bash
   pip install pandas numpy seaborn matplotlib plotly scipy scikit-learn
   ```

3. **Launch Jupyter**

   ```bash
   jupyter notebook
   ```

4. **Open the notebooks**

   - `notebooks/Adult_Income_EDA.ipynb` → basic exploration and charts (distributions, categories, relationships).
   - `notebooks/Adult_Income_Machine_Learning.ipynb` → modeling and evaluation (feature prep, models, metrics).

## Notes

- The notebooks read data from `../data/...` relative to their location in `notebooks/`.
- If you move the notebooks or data directory, update the `read_csv` paths accordingly.
