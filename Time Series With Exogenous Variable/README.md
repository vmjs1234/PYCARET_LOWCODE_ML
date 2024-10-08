COLAB LINK UPDATED https://colab.research.google.com/drive/16Vn3dRC7U8UejpzqcgFkzsJVZZ57Uq2D?usp=sharing
# Time Series Forecasting with Exogenous Variables using PyCaret

This directory contains a Jupyter notebook demonstrating time series forecasting with exogenous variables using PyCaret, a low-code machine learning library in Python.

## Notebook Contents

The notebook in this directory covers:

- Setting up PyCaret for time series forecasting
- Loading and preprocessing a time series dataset with exogenous variables (different from the official PyCaret examples)
- Training and comparing multiple time series forecasting models
- Model evaluation and interpretation
- Making future predictions

## How to Run

1. Ensure you have PyCaret installed (`pip install pycaret`)
2. Open the Jupyter notebook in this directory
3. Run the cells sequentially

Note: The notebook is set up to use GPU if available (`use_gpu=True` in the setup function).

## Dataset

The dataset used in this notebook is [[Bike sharing demand](https://www.kaggle.com/competitions/bike-sharing-demand/data)] from [Kaggle]. 

## Video Tutorial

A comprehensive video tutorial explaining this notebook and its outputs is available at [[VIDEO](https://drive.google.com/file/d/162hs26lYSjVYp5lnmUWcK9oW3k2pPjGl/view?usp=drive_link)].

## Additional Notes

- This implementation uses full AutoML capabilities of PyCaret for time series forecasting with exogenous variables.
- The code has been rewritten and is not a direct copy from PyCaret examples to ensure originality.
