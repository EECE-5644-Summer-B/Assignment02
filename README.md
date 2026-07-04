# MiniProject #02

by Patrick Donnelly & Burke Havranek

EECE 6544: Introduction to Machine Learning and Pattern Recognition

Northeastern University College of Engineering

Summer 2026, Session B

## Introduction

This repository provides a multilinear regression analysis of service data for a fictional telecommunications company, Telco. The associated Jupyter Notebook processes the given sanitized customer data given by `telco.csv`, representing the various services and resulting monthly costs of several thousand users, including other demographic information not otherwise treated, and performs a multilinear regression analysis to estimate the per-service cost at Telco.

## Installation

This document and associated codebase exists in the form of a Jupyter Notebook with various auxiliary files. No external builds should be required, though Python 3.12 or newer is recommended for guaranteed compatibility. A full list of dependencies is provided in `requirements.txt`, though all such dependencies are installed automatically by the aforementioned notebook. It is recommended to run this notebook in a Python 3.12 virtual environment, though this should not be required for functionality.

## Downloading the Dataset

The dataset in question is provided in `telco.csv`, which is not publicly available. This cleaned dataset comes prepackaged with this repository, and should not be removed from the main directory or otherwise altered in any way.

## Running the Notebook

The aforementioned notebook exists in `notebook.ipynb`, and has been engineered to run "out of the box" without additional configuration. Running the notebook from the repository directory should be sufficient.

## Summary of Findings

Given the aforementioned multilinear regression, we find the approximate monthly cost for ten services given below:

| Service | Description | Approximate Cost ($/mo) |
| ------- | ----------- | ----------------------- |
| `PhoneService` | Cost of a singular phone line to the customer | 20.05 |
| `MultipleLines` | Cost of several phone lines to the customer | 5.01 |
| `OnlineSecurity` | Cost of online security add-on | 5.01 |
| `OnlineBackup` | Cost of online backup add-on | 4.99 |
| `DeviceProtection` | Cost of device warranty add-on | 5.02 |
| `TechSupport` | Cost of customer service add-on | 5.03 |
| `StreamingTV` | Cost of TV streaming subscription | 9.97 |
| `StreamingMovies` | Cost of movie streaming subscription | 9.96 |
| `InternetService_Fiber` | Base cost of fiber optic internet | 24.96 |
| `InternetService_No` | *Reimbursement* for lack of internet service | -25.05 |
