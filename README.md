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

   - `notebooks/Adult_Income_EDA.ipynb` → basic exploration and charts.
   - `notebooks/Adult_Income_Machine_Learning.ipynb` → modeling and evaluation.
   - `notebooks/Adult_Income_EDA.ipynb` for exploration and visualization.
   - `notebooks/Adult_Income_Machine_Learning.ipynb` for modeling and evaluation.

## Notes

- The notebooks read data from `../data/...` relative to their location in `notebooks/`.
- If you move the notebooks or data directory, update the `read_csv` paths accordingly.
