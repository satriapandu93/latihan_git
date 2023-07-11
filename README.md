# Tutorial Modeling data titanic

Tutorial ini mengolah data titanic yang siap untuk pemodelan

## Prerequisites

1. Download data [here](https://www.kaggle.com/datasets/heptapod/titanic)
2. Instalasi yang dibutuhkan `pip install requirements.txt`

## Getting started

- Dataset Splitting
- Training
- Model Validation

### Dataset Splitting

split data into training, validation and test sets

`code`

X_train, y_train, X_test, y_test = dataset_splitting()

X_train.shape, y_train.shape