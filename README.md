# California House Pricing 

A beginner-friendly machine learning project to predict **_median house value_** using the California housing dataset.



## Overview
- **_Goal_**: Predict `median_house_value` from housing-related features.
- **_Status_**: The dataset is included, and `main.py` is currently a placeholder (no training pipeline yet).
- **_Next_**: Add EDA, preprocessing, model training, and evaluation.

---

## Dataset
File: `housing.csv`

- **_Target_**:
  - `median_house_value`

- **_Features_**:
  - `longitude`, `latitude`
  - `housing_median_age`
  - `total_rooms`, `total_bedrooms`
  - `population`, `households`
  - `median_income`
  - `ocean_proximity` _(categorical)_

- **_Common preprocessing needs_**:
  - Handle missing values (often in `total_bedrooms`)
  - Encode `ocean_proximity` (e.g., one-hot encoding)

---

## Project Structure
- `main.py` — entry script _(currently placeholder)_
- `housing.csv` — dataset
- `tempCodeRunnerFile.py` — editor temp file _(recommended to ignore in git)_

---

## Getting Started
### Prerequisites
- Python **3.9+** _(recommended)_

### (Optional) Create a virtual environment
- **Windows (PowerShell)**:
  - `python -m venv .venv`
  - `.venv\Scripts\Activate.ps1`

- **Git Bash**:
  - `python -m venv .venv`
  - `source .venv/Scripts/activate`

### Dependencies
- **Current**: no external dependencies required to run the placeholder `main.py`.
- **Recommended (when you build the ML pipeline)**:
  - `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

---

## How to Run
From the project folder:

- Run the script:
  - `python main.py`

---

## Planned ML Pipeline
- **_1) EDA (Exploratory Data Analysis)_**
  - Check missing values
  - Plot distributions
  - Look at correlations
  - Inspect `ocean_proximity` categories

- **_2) Train/Test Split_**
  - Create a reproducible split with a fixed random seed

- **_3) Preprocessing_**
  - Impute missing numeric values (e.g., median strategy)
  - One-hot encode `ocean_proximity`
  - Optional scaling for linear models

- **_4) Modeling_**
  - Baseline: Linear Regression
  - Stronger: Random Forest / Gradient Boosting

- **_5) Save Artifacts_**
  - Save the trained model + preprocessing pipeline

---

## Evaluation
- **_Metrics_**:
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Squared Error)

- **_Validation approach_**:
  - Train/validation split or cross-validation

---

## Results
- **_Baseline model_**: _TBD_
- **_Best model_**: _TBD_
- **_RMSE / MAE_**: _TBD_

_(Fill this section after implementing training + evaluation.)_

---

## Notes
- `ocean_proximity` is categorical and must be encoded.
- If you publish this repo, consider not committing large datasets unless you intend to (or use Git LFS).

---

## Contributing
- Fork the repo
- Create a branch: `feature/your-change`
- Open a pull request with a short summary and test notes
---

## Acknowledgements
- California housing dataset widely used for ML practice and coursework.
