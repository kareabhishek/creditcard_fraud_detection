# Credit Card Fraud Detection

## Project Overview
This project addresses the rising issue of credit/debit card fraud in the financial sector, specifically for Finex, a Florida-based financial service provider. Fraudulent transactions have severely impacted the bank’s revenue and customer trust. As a data analyst, I built a comprehensive fraud detection system using machine learning, accompanied by root cause analysis and cost-benefit evaluation to measure its business impact.

## Business Problem
Finex is facing increasing financial losses and customer dissatisfaction due to unauthorized credit card transactions caused by:

Skimming at ATMs/POS terminals

Stolen or lost credit cards

Data breaches and account hacking

Despite customer complaints, late reporting has made it difficult for Finex to recover funds or prevent repeat fraud. The bank lacks a proactive fraud detection system and relies heavily on outdated manual processes.

## Objectives
Analyze the root causes of increasing fraudulent transactions

Build a fraud detection system using machine learning

Evaluate the model's performance using appropriate metrics

Conduct a cost-benefit analysis to demonstrate business impact

Recommend strategies for risk mitigation and customer trust improvement

## Tools & Technologies
Python, Pandas, NumPy

Scikit-learn, XGBoost, SMOTE

Matplotlib, Seaborn (for EDA and visualizations)

Google Colab (Notebook execution)

Coggle (Issue tree for root cause analysis)

PowerPoint & Video Tools (For stakeholder presentation)

## Project Pipeline
1. Business Understanding
Created an Issue Tree to identify root causes of fraud

Focused on detecting, not apprehending, fraudsters

Highlighted bottlenecks in the transaction process

2. Data Understanding
Dataset: 1.8M+ transactions from ~1,000 cardholders (2019–2020)

Fraudulent transactions: ~9,651 (0.52%)

Highly imbalanced binary classification problem

3. Exploratory Data Analysis (EDA)
Univariate and bivariate analysis

Outlier detection

Skewness checks and feature transformations

4. Handling Imbalanced Data
Applied SMOTE to oversample fraud cases

Compared performance with and without resampling

5. Model Building
Baseline: Logistic Regression

Advanced: Random Forest, XGBoost

Applied Stratified K-Fold Cross Validation

Hyperparameter tuning via GridSearchCV

6. Model Evaluation
Focused on metrics suitable for imbalanced data:

Precision

Recall

F1-Score

AUC-ROC Curve

7. Cost-Benefit Analysis
Part I:
Calculated:

Avg. transactions/month

Avg. frauds/month

Avg. loss per fraud

Part II:
Compared:

Monthly losses before model (full reimbursement)

Monthly losses after model (partial support + undetected fraud)

Final Savings = Before – After

## Final Presentation
Delivered findings through a PowerPoint deck and an explainer video for stakeholders.

Covered insights, business impact, and recommendations.

## Key Insights
Significant heteroscedasticity in transaction patterns

Fraud mostly occurs during non-peak hours

Model achieved high recall while minimizing false positives

Projected savings for Finex: $X per month (calculated in notebook)

## Business Impact
By deploying the model:

Real-time fraud detection without inconveniencing customers

Reduction in monthly losses from fraud reimbursement

Improved customer experience via proactive communication

Long-term cost savings through automation and targeted alerts

## Files Included
fraud_detection_notebook.ipynb – Full ML pipeline & analysis

EDA_visuals/ – Charts and plots from the exploratory analysis

cost_benefit_calculation.xlsx – Monthly savings breakdown

issue_tree_coggle.pdf – Root cause analysis diagram

presentation.pptx – Business stakeholder deck

project_video.mp4 – Final walkthrough video

## Skills Demonstrated
Business understanding and stakeholder communication

Data cleaning, EDA, and statistical analysis

Machine learning model building and evaluation

Handling imbalanced classification

Cost-benefit and financial impact analysis

Visualization and storytelling
