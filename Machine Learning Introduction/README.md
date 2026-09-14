# Machine Learning Introduction

An introductory classification exercise that builds a food-allergy prediction target from patient records and prepares features for machine-learning modeling.

## What it covers

- Load patient data from the food-allergy dataset.
- Engineer a binary `has_food_allergy` target from individual allergy fields.
- Guard against data leakage by excluding direct allergy fields from predictors.
- Use demographic attributes and related health conditions as candidate features.
- Build a preprocessing pipeline before model training.

## Files

- `Machine Learning_Introduction_Homework.ipynb` — data preparation, feature engineering, and modeling exercise.
- `food-allergy-analysis-Zenodo.csv` — source dataset.
- `Description Introduction to Machine Learning practice.pdf` — task brief.

## Run

The dataset is large, so allow sufficient memory and time when loading it. Install Jupyter, Pandas, NumPy, and scikit-learn, then run the notebook from top to bottom.
