# Home Credit Default Risk — Algorithmic Fairness Audit

**NYU Responsible Data Science | Fall 2026**

## Overview

This project audits two automated decision systems (ADS) developed for the [Home Credit Default Risk Kaggle Competition](https://www.kaggle.com/competitions/home-credit-default-risk), which predicts whether loan applicants will experience repayment difficulties.

We investigate potential algorithmic biases in credit risk prediction, focusing on data representation, fairness across applicant groups, and disparities in model outcomes.

## Systems Under Audit

We examine two independently developed machine learning approaches:

1. **LightGBM:** A gradient-boosted decision tree model ([Original Kaggle Notebook](https://www.kaggle.com/code/kloudnine/home-credit-default-risk/notebook)).
2. **Neural Network:** A neural network incorporating convolution over previous loan applications and credit bureau records ([Original Kaggle Notebook](https://www.kaggle.com/code/aaraneo/nn-with-convolution-over-prev-app-and-bureau/log)).

## Repository Structure

- `data/` — Home Credit competition datasets
- `lightgbm/` — LightGBM model and audit materials
- `neuralnetwork/` — Neural network model and audit materials

## Attribution

The original model notebooks and competition datasets are sourced from Kaggle and **are not our original work**. Our contributions focus on independently auditing these systems for algorithmic fairness.

## Project Team

Ashley Funes, Jenny Hong, Emma Zhang, Sarah Liu

**Status:** Work in progress.
