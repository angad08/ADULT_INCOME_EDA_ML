# Adult Census Income Dataset: EDA & ML

## About

I built this project to show how I think through a real dataset from start to finish — not just coding, but the logic behind each step. The Adult Census Income dataset (often called the “Adult Income” dataset) is a classic dataset with demographic and work‑related features and an income label. My goal here is to make the work clear, honest, and easy to follow, whether you’re technical or not.

## What’s inside
# Adult Income EDA & ML

## About

This repo is my place to explore the Adult Income dataset and try a few machine‑learning ideas. If you are new to data work, that’s totally fine — the notebooks are meant to be opened and followed step by step.

## What’s inside
I put this together to keep my Adult Income EDA and modeling work in one place. It’s meant to be simple to open, run, and tweak as I explore the data and try different ML approaches.

## Project structure

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
## Getting started

1. **Create a virtual environment (optional)**

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

## What I did (high‑level, step by step)

1. **Framed the problem**  
   The goal is to understand patterns in income using demographic and work‑related features.

2. **Loaded and sanity‑checked the data**  
   Checked shape, column types, and any suspicious or missing values.

3. **Cleaned the data carefully**  
   Handled “?” entries in categorical columns and confirmed categories looked reasonable.

4. **Explored the data visually and statistically**  
   Looked at distributions, group comparisons, and relationships between variables.

5. **Prepared features for modeling**  
   Converted categorical values, engineered simple features, and set up train/test splits.

6. **Trained baseline models and evaluated them**  
   Trained models and compared metrics to understand performance and trade‑offs.

## Why this matters (for data roles)

I wanted this repo to show that I can go beyond running code — I can explain what I’m doing, why I’m doing it, and what the results mean. If you’re a hiring manager or recruiter in data, you’ll see clean structure, practical analysis, and a clear story from raw data to model evaluation.
   - `notebooks/Adult_Income_EDA.ipynb` for exploration and visualization.
   - `notebooks/Adult_Income_Machine_Learning.ipynb` for modeling and evaluation.

## Notes

- The notebooks read data from `../data/...` relative to their location in `notebooks/`.
- If you move the notebooks or data directory, update the `read_csv` paths accordingly.
