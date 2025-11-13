# Fairness Analysis on the Adult Census Dataset

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-green)
![Status](https://img.shields.io/badge/Project-Active-success)

A simple and practical demonstration of **fairness evaluation in machine learning**, using the Adult Census dataset as a proxy for a loan-approval classifier.

This mini-project shows:

- How to train a Logistic Regression model  
- How to compute accuracy  
- How to evaluate fairness across gender groups  
- How to calculate *selection rate disparity*  
- How to visualize fairness differences  

This project is part of my continuous learning journey in **AIOps, Responsible AI, and ML fairness**.

---

## 📘 Project Overview

Traditional ML evaluations often focus only on metrics like **accuracy**.  
However, ML models can still behave unfairly toward specific groups.

This project evaluates:

- **Accuracy per group (Female vs Male)**  
- **Selection rate per group**  
- **Fairness disparity = max(selection_rate) – min(selection_rate)**  

---

## 📂 Repository Structure
