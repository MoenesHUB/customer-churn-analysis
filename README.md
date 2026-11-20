# Customer Churn Analysis (CRISP-DM)

University project: analysing why customers leave a telecommunications company, following the CRISP-DM methodology.

## Project structure

```
ML/
├── data/
│   └── Telco-Customer-Churn.csv      # dataset (7,043 customers, 21 columns)
├── Customer_Churn_Analysis.ipynb     # the notebook (all 6 CRISP-DM phases)
├── requirements.txt                  # Python libraries needed
└── README.md
```

## Dataset

- **IBM Telco Customer Churn**: a sample dataset published by IBM about a fictional telecom company in California.
- Source: https://github.com/IBM/telco-customer-churn-on-icp4d/blob/master/data/Telco-Customer-Churn.csv
- Also available on Kaggle: "Telco Customer Churn" (blastchar).

## How to run

1. Install Python 3 (https://www.python.org/downloads/ – tick "Add Python to PATH").
2. In a terminal opened in this folder:
   ```
   python -m pip install -r requirements.txt
   ```
3. Open `Customer_Churn_Analysis.ipynb` in VS Code, select the Python 3.12 kernel (top right) and click **Run All**.
   Or, without VS Code: run `python -m notebook` and open the file in the browser.
