# ASI_Dropout_Reproduction

This repository contains the official codebase for the reproduction of the seminal paper *"Dropout as a Bayesian Approximation: Representing Model Uncertainty in Deep Learning"* (Gal & Ghahramani, 2016). 

The notebook validates the Monte Carlo (MC) Dropout inference protocol across four distinct experiments (1D regression extrapolation, MNIST image classification, Boston Housing quantitative evaluation, and RL Thompson Sampling) to demonstrate its ability to estimate model uncertainty.

## 📦 Dependencies

To execute the notebook successfully, please ensure the following core libraries are installed in your Python environment:

* `torch` & `torchvision` (PyTorch framework)
* `numpy` & `pandas` (Data manipulation)
* `matplotlib` (Visualization)
* `scikit-learn` (Data scaling and splitting)
* `optuna` (Bayesian Optimization for hyperparameter tuning)

## 🚀 How to Run

Simply open the `asi.ipynb` notebook in Jupyter and run all cells sequentially from top to bottom. The notebook is self-contained and will automatically download the required datasets (e.g., MNIST, Boston Housing) during execution.
