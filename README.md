@"
# Fraud Detection System

End-to-end fraud detection pipeline — from EDA to a deployed, explainable, real-time API and dashboard. Built on the ULB Credit Card Fraud dataset (284,807 transactions, 492 frauds, ~0.17% fraud rate).

## Problem Statement
(Write after Phase 1 EDA)

## Approach
1. EDA — class distribution, feature/time patterns
2. Unsupervised baseline — Isolation Forest, Autoencoder
3. Supervised modeling — XGBoost/LightGBM + imbalance handling
4. Evaluation — Precision-Recall curve, cost-based threshold tuning
5. Explainability — SHAP
6. Production API — FastAPI /predict
7. Dashboard — Streamlit
8. Deployment — Docker + Streamlit Cloud + Render

## Setup
