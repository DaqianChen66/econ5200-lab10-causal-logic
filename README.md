# econ5200-lab10-causal-logic
# ECON 5200 Lab 10: Causal Logic

This repository contains my work for Lab 10 on correlation, causality, and bad controls.

## Files

- `lab-ch10-diagnostic.ipynb` — main lab notebook
- `src/dag_utils.py` — helper functions for checking DAG adjustment sets

## Topics

This lab covers:

- collider bias
- pre-treatment controls
- total vs direct effects
- backdoor paths
- valid adjustment sets
- the LaLonde example
- sensitivity to unobserved confounding

## Main Idea

A variable should not be controlled for just because it is observed before treatment or improves model fit. Control variables should be chosen based on the causal graph and the estimand of interest.

## How to Run

Open the notebook and run the cells from top to bottom.

Required Python packages include:

`numpy`, `pandas`, `matplotlib`, `networkx`, and `statsmodels`.
