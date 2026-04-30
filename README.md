# Bayesian Network for Loan Risk Prediction

A walk-through of how to build a Bayesian network in Python to predict
the probability that a loan goes bad, using a 25,000-loan sample from
Lending Club. Demonstrates how prior beliefs about borrower
characteristics get updated into posterior risk estimates as evidence
(FICO, DTI, income, loan purpose, etc.) is observed.

## Files
- `Bayes_Analysis_For_Predicting_Risk.ipynb` — the tutorial notebook

## Data
`lendingclub_sample_25000.csv` is included in the repo. The notebook
expects it at `c:\risk\lendingclub_sample_25000.csv`, so create that
folder and copy the file there before running.

## Requirements
pandas · numpy · pgmpy · scikit-learn · matplotlib

## Usage
Open the notebook in Jupyter and run all cells.
