# Exploring Local Outlier Factor

This notebook is a small anomaly-detection experiment with scikit-learn's Local Outlier Factor (LOF). I created it while studying how local-density methods can help identify unusual observations, including possible fraud cases.

The current example works with the `sepal_length` and `sepal_width` columns from a CSV file and compares the LOF output with simple visualizations and a K-means experiment.

## What the notebook covers

- loading and plotting a two-feature dataset
- fitting `LocalOutlierFactor`
- identifying observations marked as outliers
- visualizing the decision boundary and detected points
- comparing the structure with K-means clustering

## Running it

Open `LOF_jadid.ipynb` in Jupyter or Google Colab. You will need pandas, NumPy, Matplotlib, Seaborn, and scikit-learn.

The notebook expects a file named `3.csv`, which is not included in this repository. Provide a CSV with the expected columns or update the loading and column-selection cells for your own dataset.

## Note

This is an exploratory example, not a validated fraud-detection system. LOF results depend strongly on the chosen features, scaling, neighbourhood size, and the data distribution.
