# California House Price Prediction 🏠

[![Python Version](https://img.shields.io/badge/python-3.9%2B-blue.svg)](https://www.python.org/downloads/)
[![Status](https://img.shields.io/badge/status-WIP-orange.svg)](#)

A professional, beginner-friendly machine learning project designed to predict **median house values** in California. This repository serves as a foundation for building a complete regression pipeline, from exploratory data analysis to model deployment.

---

## 📌 Overview

The goal of this project is to leverage the California Housing dataset to predict the `median_house_value` based on various demographic and geographic features. 

**Current Project Status:**
* [x] Dataset integrated (`housing.csv`)
* [ ] Exploratory Data Analysis (EDA)
* [ ] Feature Engineering & Preprocessing
* [ ] Model Training & Hyperparameter Tuning
* [ ] Performance Evaluation

---

## 📊 Dataset Summary

The dataset contains information from the 1990 California census.

| Feature | Description |
| :--- | :--- |
| **Target Variable** | `median_house_value` |
| **Geographic** | `longitude`, `latitude` |
| **Property Details** | `housing_median_age`, `total_rooms`, `total_bedrooms` |
| **Demographics** | `population`, `households`, `median_income` |
| **Categorical** | `ocean_proximity` (e.g., `<1H OCEAN`, `INLAND`) |

> **Note:** Initial inspection shows missing values in the `total_bedrooms` column, which will require imputation during the preprocessing phase.

---

## 📂 Project Structure

```text
.
├── main.py              # Main entry point for the application
├── housing.csv          # Raw dataset file
├── .gitignore           # Standard Python gitignore (ignores .venv, temp files)
└── README.md            # Project documentation
