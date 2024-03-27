# Analysis of Fundamental Financial Metrics

This repository contains an analysis of the dataset "fundamentals.csv", which includes metrics extracted from annual SEC 10K filings for the years 2012-2016. The dataset comprises 1781 observations and 78 attributes.

## Contents

1. [Data Exploration and Visualization](#data-exploration-and-visualization)
2. [Linear Regression Model Development](#linear-regression-model-development)
3. [Multicollinearity in Linear Regression](#multicollinearity-in-linear-regression)
4. [P-Value Analysis and Histogram](#p-value-analysis-and-histogram)
5. [False Discovery Rate Control with BH Procedure](#false-discovery-rate-control-with-bh-procedure)
6. [Sensitivity Analysis of FDR Control](#sensitivity-analysis-of-fdr-control)
7. [Exploring Interaction Terms](#exploring-interaction-terms)
8. [Model Evaluation with Interaction Terms](#model-evaluation-with-interaction-terms)
9. [FDR Analysis with Interaction Terms](#fdr-analysis-with-interaction-terms)

## Data Exploration and Visualization

Explored the dataset "fundamentals.csv", including various plots for visualization and insight generation.

## Linear Regression Model Development

Developed a linear regression model to predict Estimated Shares Outstanding and provided an explanation of the model.

## Multicollinearity in Linear Regression

Explained how multicollinearity can affect the interpretation of coefficients in a linear regression model.

## P-Value Analysis and Histogram

Created a histogram of p-values to assess their distribution for skewedness and provided an explanation.

## False Discovery Rate Control with BH Procedure

Used the Benjamini-Hochberg (BH) procedure to control the False Discovery Rate (FDR) with a q-value of 0.1 and estimated the number of "true" discoveries.

## Sensitivity Analysis of FDR Control

Analyzed the sensitivity of FDR control by applying the BH procedure at different q-values and discussed the robustness of significant variables.

## Exploring Interaction Terms

Expanded the linear regression model by adding interaction terms and created interaction terms between pairs of predictors, including explanations on their importance.

## Model Evaluation with Interaction Terms

Evaluated the performance of the new model with interaction terms, compared it with the original model, and discussed significant changes in performance or coefficients.

## FDR Analysis with Interaction Terms

Created a histogram of p-values for the new model with interaction terms, applied the BH procedure to control FDR with a q-value of 0.1, and compared results with the original model.

---

This document serves as a summary of the analysis steps, methodologies, and findings conducted on the dataset "fundamentals.csv".
