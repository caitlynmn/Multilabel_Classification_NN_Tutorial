# Multilabel Classification Neural Network Tutorial
By: Caitlyn Nguyen

## Introduction
Traditional modelling frameworks are designed to predict a single label, l, from a set of disjoint labels, L. This type of learning problem is known as single-label classification (SLC). When predicting from only |L|  = 2 set of disjoint labels, this SLC problem can be called binary classification (BC). When predicting for only one label from a set of mutually exclusive labels where |L|  > 2, this SLC is known as multi-class classification (MCC). Both BC and MCC are focused on predicting a single label from the disjoint labels, L. Alternatively, one could predict for a set of multiple related, non-exclusive classes, Y, where Y⊆L. This type of prediction is known as multi-label classification (MLC).

This tutorial will review how to create a multi-label classification neural network using torch. This tutorial was created using Python 3.10.9, numpy 1.23.5, pandas 1.5.2, matplotlib 3.7.1, scikit-learn 1.2.2, torch 2.0.0, and shap 0.41.0, and jupyter 1.0.0.

## Repository Contents
The document `Multilabel_Tutorial.docx` is a tutorial on how to construct a multi-label classification neural network. The Jupyter noteboook `MLC_Tutorial.ipynb` contains the code that was used for the tutorial.
