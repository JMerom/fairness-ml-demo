# Fairness Analysis on the Adult Census Dataset  

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange" />
  <img src="https://img.shields.io/badge/scikit--learn-ML-green" />
  <img src="https://img.shields.io/badge/Responsible%20AI-Fairness-teal" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
  <img src="https://img.shields.io/github/last-commit/JMerom/fairness-ml-demo?color=blue" />
</p>

A simple and practical demonstration of **fairness evaluation in machine learning**, using the Adult Census dataset as a proxy for a loan-approval classification task.

This mini-project demonstrates:

- How to train a Logistic Regression model  
- How to compute model accuracy  
- How to evaluate fairness across gender groups  
- How to calculate **selection rate disparity**  
- How to visualize fairness differences  
- How ML models can unintentionally behave unfairly  

This project is part of my continuous learning journey in **AIOps, Responsible AI, and ML fairness**.

---

## 📘 Project Overview

Traditional ML evaluations often focus only on metrics like **accuracy**.  
However, ML models may still behave unfairly toward specific demographic groups — especially in domains like finance, hiring, or healthcare.

This project evaluates:

- **Accuracy per group** (Female vs Male)  
- **Selection rate per group**  
- **Fairness disparity** = max(selection_rate) − min(selection_rate)

This provides an accessible introduction to **algorithmic fairness**, helping users understand how the same model behaves across different slices of data.

---
