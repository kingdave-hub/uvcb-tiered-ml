# UVCB Tiered Machine Learning Project

This repository contains a reproducible machine learning pipeline developed to support tiered toxicity evaluation of petroleum UVCB substances using transcriptomic and phenotypic data.

## Project Objective

To evaluate predictive models capable of identifying representative petroleum substances for toxicity testing using in vitro transcriptomic signatures.

## Dataset

iPSC Hepatocyte dataset containing approximately 140 petroleum UVCB treatments with ~2100 transcriptomic predictors.

## Modeling Strategy

The project compares multiple machine learning approaches:

- Elastic Net Regularized Regression
- Random Forest
- XGBoost Gradient Boosting

Models are evaluated using repeated cross-validation.

## Key Endpoint

Primary endpoint used for tiered prioritization:

median_log10ppod

This endpoint represents the median potency estimate derived from transcriptomic response data.


