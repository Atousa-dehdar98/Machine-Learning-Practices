# Hepatitis C Classification and Clustering

An end-to-end machine-learning project using hepatitis C laboratory data. It combines preprocessing, unsupervised clustering, supervised classification, and a final comparison of both approaches.

## Project stages

1. **Data cleaning** — prepare the raw hepatitis C dataset, handle data types and missing values, and produce a cleaned data file.
2. **Unsupervised learning** — apply Agglomerative Clustering without the diagnosis target and save cluster assignments.
3. **Supervised learning** — train and evaluate a `RandomForestClassifier` using the prepared data.
4. **Conclusion** — compare actual labels, predicted classes, and cluster composition on the test set.

## Files

- `1. Data cleaning.ipynb` through `4. Conclusion.ipynb` — the four project stages.
- `HepatitisCdata.csv` — original dataset.
- `HepatitisCdata_cleaned.csv` and `clustered_HepatitisC.csv` — intermediate prepared datasets.
- `test_summary.csv` — test-set results for the final comparison.
- `Description of Hepatitis-C-Classification-and-Clustering practice.pdf` — task brief.

## Run

Run the notebooks in numbered order. Each stage uses the outputs created in the previous one.
