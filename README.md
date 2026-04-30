# Bayesian Network for Loan Risk Prediction

A walk-through of how to build a Bayesian network in Python to predict
the probability that a loan goes bad, using a 25,000-loan sample from
Lending Club. Demonstrates how prior beliefs about borrower
characteristics get updated into posterior risk estimates as evidence
(FICO, DTI, income, loan purpose, etc.) is observed.

## Files
- `Bayes_Analysis_For_Predicting_Risk.ipynb` — the tutorial notebook

## Data
The notebook reads `lendingclub_sample_25000.csv` from `c:\risk\` and
writes results to the same folder. Create a `c:\risk\` directory and
drop the Lending Club sample CSV there before running.

## Requirements
pandas · numpy · pgmpy · scikit-learn · matplotlib

## Usage
Open the notebook in Jupyter and run all cells.
