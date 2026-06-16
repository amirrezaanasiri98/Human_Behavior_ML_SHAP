# A Novel Hybrid Structural Equation Modeling–Machine Learning Framework for Identifying Key Predictors of Pro-Environmental Behavior: A Study of Urban Cycling

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📌 Overview
This repository contains the Machine Learning (ML) and SHAP (SHapley Additive exPlanations) analysis code for the research paper: **"A Novel Hybrid Structural Equation Modeling–Machine Learning Framework for Identifying Key Predictors of Pro-Environmental Behavior: A Study of Urban Cycling"**.

The study proposes a hybrid analytical framework integrating Structural Equation Modeling (SEM) and Machine Learning (Random Forest) grounded in the Extended Theory of Planned Behavior (ETPB). While SEM validates causal relationships, the ML component captures non-linear associations and latent interaction effects among variables. SHAP analysis is applied to improve the interpretability of ML outcomes, revealing the relative importance and functional impact of each predictor (e.g., psychological barriers vs. physical constraints like topographical slope).

## 📊 Abstract
This study proposes a hybrid analytical framework integrating structural equation modeling (SEM) and machine learning (ML) to investigate the socio-psychological predictors influencing citizens’ cycling behavior within a metropolitan context. The framework is grounded in the extended theory of planned behavior (ETPB), which incorporates moral norms to address limitations of the classical TPB model in explaining pro-environmental behavior. 

Although SEM is widely used to validate causal relationships among theoretical constructs, it has limitations in capturing non-linear associations and latent interaction effects among variables. To overcome these limitations, this study integrates ML with SEM. In addition, Shapley additive explanations (SHAP) are applied to improve the interpretability of ML outcomes. 

The ML model achieved an $R^2$ value of 0.81 for the behavior component and revealed patterns not captured by SEM. The proposed framework uncovered non-linear relationships and interaction effects, including the moderating role of age in the attitude–intention relationship and the limited influence of topographical slope compared to psychological bottlenecks.

## 📁 Repository Structure
*   `Human_Behavior_ML_SHAP.ipynb`: The main Jupyter Notebook containing data preprocessing, Random Forest model training, evaluation metrics, and SHAP visualizations (Summary plots, Dependence plots, and Interaction analyses).
*   `TEH_ML.xlsx`: The dataset used for ML analysis (Ensure this is in the same directory as the notebook).
*   `requirements.txt`: List of Python dependencies required to run the code.

## ⚙️ Requirements
To run the code, you need Python 3.8+ and the following libraries:
```bash
pip install pandas numpy scikit-learn shap matplotlib openpyxl

## 🚀 Usage
1. Clone this repository:
   
```bash
   git clone https://github.com/YOUR-USERNAME/Human_Behavior_ML_SHAP.git
