# Adult Income EDA & ML

This repository contains exploratory data analysis (EDA) and machine learning (ML) notebooks for the Adult Income dataset.

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

   - `notebooks/Adult_Income_EDA.ipynb` for exploration and visualization.
   - `notebooks/Adult_Income_Machine_Learning.ipynb` for modeling and evaluation.

## Notes

- The notebooks read data from `../data/...` relative to their location in `notebooks/`.
- If you move the notebooks or data directory, update the `read_csv` paths accordingly.
