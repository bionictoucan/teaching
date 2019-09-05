# Tutorial for ML-Helio Conference 17th September 2019

This is the repository for the first of two tutorials given at the Machine Learning in Heliophysics conference in Amsterdam, NL 16-20 September 2019. This first tutorial will explore how to get started with machine learning in Python and is primarily aimed at people new to the subject. There will be three main topics explored which are crucial for ML:

1. How to prepare a dataset for use with ML algorithms.
2. Using classical ML methods from the `scikit-learn` Python package for regression purposes.
3. Using the deep learning library `PyTorch` for building neural networks.

The dataset we will use throughout this tutorial is the monthly sunspot number from 1750&ndash;present provided by the [Royal Observatory of Belgium](http://sidc.be/silso/home). The idea is to train models to predict the next solar cycle's sunspot numbers using various different regression techniques. The data is in the file `SN_m_tot_V2.0.csv`.

All of the analysis is included in the `ml_helio_tutorial_1.ipynb` Jupyter notebook and will be able to be followed interactively throughout. If you would like to interactively follow along or play with the notebook after please use the following instructions for installing the virtual environment containing all necessary packages (provided the user is using conda):

```bash
>>> conda env create -f ml-helio.yml
>>> conda activate ml-helio
```
