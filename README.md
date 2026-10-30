# DSCI 552 Homework 5

Shanglin Jiang

## Files

- `notebook/Jiang_Shanglin_HW5.ipynb`: executed solutions to Questions 1 and 2.
- `data/`: supplied data and descriptions, unchanged.
- `results/`: figures, CV results, selected coefficients, and test predictions.
- `requirements.txt`: Python dependencies.

## Run

Tested with Python 3.10. Install the dependencies with `pip install -r requirements.txt`.
Open the notebook with its working directory set to `notebook/`, then restart the kernel and run all cells.
The notebook uses relative paths and runs all model searches locally. Searches may take several minutes.
On macOS, XGBoost may require the OpenMP runtime (`brew install libomp`).

Regression uses the prescribed first 1495 rows for training and the remaining 499 for testing.
Preprocessing and parameter selection use training data only. Test error is MSE.
