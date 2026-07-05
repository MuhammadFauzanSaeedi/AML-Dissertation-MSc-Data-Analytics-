# AML-Dissertation-MSc-Data-Analytics-

Comparative Analysis of Machine Learning Classification Models for Anti-Money Laundering Detection

MSc Data Analytics Dissertation
Berlin School of Business and Innovation (BSBI)
In affiliation with the University for the Creative Arts (UCA)
Author: Muhammad Fauzan
Supervisor: Dr. Christos Lemonakis
Submission Year: 2026

# Overview

This repository contains the complete Python implementation, dataset files, and final dissertation document for the MSc Data Analytics dissertation titled:

"Comparative Analysis of Machine Learning Classification Models for Anti-Money Laundering Detection"

The study conducted a rigorous comparative analysis of six supervised machine learning classification algorithms applied to the IBM Transactions for Anti-Money Laundering (AML) dataset, complemented by primary research comprising a survey of twelve AML and compliance professionals.

# Research Summary

## Problem Statement

Traditional rule-based AML transaction monitoring systems generate false positive rates of 90–95%, overwhelming compliance teams and failing to detect novel laundering patterns. Machine learning classification models offer a data-driven alternative, but comparative evaluations across multiple algorithms under consistent conditions remain limited in the literature — particularly in Islamic banking and emerging market contexts.

## Dataset

The IBM Transactions for Anti-Money Laundering (AML) dataset (HI-Medium variant) was used, published by Altman et al. (2023) at the 37th Conference on Neural Information Processing Systems (NeurIPS 2023). A stratified 7% sample comprising 2,232,877 transactions was drawn, of which 2,466 (0.11%) were labelled as laundering cases, reflecting real-world class imbalance conditions.

### Note: 
The IBM HI-Medium dataset files exceed GitHub's file size limit. The dataset is publicly available for download from Kaggle at:
https://www.kaggle.com/code/tameemalshomari/ibm-transactions-for-anti-money-laundering-aml

## Models Compared

Six supervised classification algorithms were trained and evaluated:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost (Gradient Boosting)
* Neural Network (MLP Classifier)
* Support Vector Machine (LinearSVC)
