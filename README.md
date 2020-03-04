# What-a-causality
# Causal and Survival Modeling
# Introduction
Churn is a problem for all companies because it represents the ratio of clients that won't use or buy again your product, the main purpose of this analysis is to find every condition a churn client has for a Doctors webpage (Marketplace). 
As the classification is provided by local CRM, almost every variable is calculated with this software, except tenure which comes from invoice dates.
The analysis will be implemented using Causality with Bayesian Networks to identify the most important variables so the next step will be Survival analysis (Kaplan-Meier) comparing churn with these varibales.

#Data 
First two datasets are provided by local CRM, invoice datasets provided by local wh. 

# Models 
# CausalNex
Using https://causalnex.readthedocs.io/en/latest/ to estimate the most important variables or how are implicated.

# Survivial model (Kaplan Meier)
After stablishing every probabilities combination, to validate CausalNex result, Kaplan Meier estimator calculates the retention percetentage for tenure days with the most significant variables.
