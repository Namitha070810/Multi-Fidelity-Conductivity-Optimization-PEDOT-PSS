# Multi-Fidelity Conductivity Optimization of PEDOT:PSS

## 📌 Overview
This project focuses on the computational optimization of **PEDOT:PSS thin-film electrical conductivity**
using **machine learning** and **multi-fidelity Bayesian optimization**.
The aim is to identify optimal **PSS molecular weight** and processing parameters
that maximize conductivity while reducing experimental effort.

---

## 🎯 Objectives
- Predict PEDOT:PSS film conductivity using machine learning models
- Analyze key processing and structural parameters influencing conductivity
- Optimize processing parameters using **Multi-Fidelity Bayesian Optimization (MF-BO)**
- Demonstrate a scalable, data-driven materials design workflow

---

## 🧪 Methodology
- **High-fidelity experimental data** collected from literature
- **Low-fidelity synthetic data** generated using trend-based physical relationships
- **Machine Learning Models Used:**
  - Random Forest Regressor
  - Gradient Boosting Regressor
 
- **Optimization Technique:**
  - Multi-Fidelity Bayesian Optimization with Expected Improvement (EI) acquisition function
- **Model Interpretability:**
  - SHAP (SHapley Additive exPlanations) analysis for feature importance


## 📊 Dataset Description
The dataset includes both high-fidelity experimental values collected from literature
and low-fidelity synthetic data generated using trend-based physical models.
Key features include PSS molecular weight, DMSO concentration, annealing temperature,
viscosity, Raman quinoid fraction, and GIWAXS π–π stacking distance.

## 🎓 Academic Context
This project was developed as part of a Mathematics course project and demonstrates
the application of optimization techniques, probability, and machine learning
in materials science.

---

## 📁 Repository Structure
