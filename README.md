# Breast Cancer Classification

## About the project

This beginner project uses a breast-cancer dataset to predict whether a
diagnosis is benign or malignant. The notebook uses Logistic Regression, a
basic binary classification model.

## Files

- `Task4.ipynb` contains the five-step analysis and charts.
- `data.csv` contains the dataset used by the notebook.

## What the notebook does

1. Loads and previews the dataset.
2. Checks for missing values, removes empty or unneeded columns, and fills
   missing numbers with the median.
3. Splits the data into training, validation, and test groups, then scales
   the features.
4. Trains Logistic Regression and shows precision, recall, a confusion
   matrix, and an ROC curve.
5. Chooses a classification threshold using validation data and shows a
   confusion-matrix chart for the tuned threshold.

The diagnosis is encoded as `0` for benign and `1` for malignant. The sigmoid
function turns the model's score into a probability from 0 to 1. The threshold
is the probability cutoff used to choose a class.

## Charts

The notebook displays diagnosis counts, any missing values found, an ROC
curve, and a confusion matrix. The ROC-AUC score summarizes how well the
model separates the two classes across thresholds.

## How to run

1. Keep `Task4.ipynb` and `data.csv` in the same folder.
2. Open the notebook in Jupyter Notebook or VS Code.
3. Run the five cells from top to bottom.

The notebook uses Python with pandas, matplotlib, and scikit-learn.
