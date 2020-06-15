# ML based reource predictor

> A Novel Recurrent Neural Network based Resource Request Scheme Minimizing RACH Preamble Collisions in 3GPP LTE-A Networks.

## Table of contents

* [data_preprocessing](https://github.com/wicky1234444/ML-based-resource-predictor/tree/master/data_preprocessing)
* [data](https://github.com/wicky1234444/ML-based-resource-predictor/tree/master/data)
* [Resource_predictors](https://github.com/wicky1234444/ML-based-resource-predictor/tree/master/Resource%20predictors)
* [Graphs](https://github.com/wicky1234444/ML-based-resource-predictor/tree/master/Graphs)

## data_preprocessing

> data_preprocessing folder contains the following files.

* [dataset statistics](<https://github.com/wicky1234444/ML-based-resource-predictor/tree/master/data_preprocessing/dataset statistics.ipynb>)

    *Contains code for checking the statistics of original calls dataset and some preprocessing.*

* [Synthetic data generation and preprocessing](<https://github.com/wicky1234444/ML-based-resource-predictor/tree/master/data_preprocessing/Synthetic data generation and preprocessing.ipynb>)

    *Contains code for synthetic dataset generation from existing data and preprocessing for the neewly generated data.*

* [collision rate calculation](<https://github.com/wicky1234444/ML-based-resource-predictor/tree/master/data_preprocessing/collision rate calculation.ipynb>)

    *Contains code for collision rate calculation from the RNN predicitons, RACH predictions and comparing the performance of MLP and RNN.*

## data

> data folder contains the training data used for training RNN, MLP models and the RNN predictions and True data in the results subfolder.

## Resource_predictors

> Contains the following code files.

* [MLP resource predictor](<https://github.com/wicky1234444/ML-based-resource-predictor/blob/master/Resource%20predictors/MLP%20resource%20predictor.ipynb>)

    *Contains Multilayer perceptron based resource predictor model and its training code*

* [RNN resource predictor](<https://github.com/wicky1234444/ML-based-resource-predictor/blob/master/Resource%20predictors/RNN%20resource%20predictor.ipynb>)

    *Contains RNN based resource predictor model, its training and request predictions generation code*

## Graphs

> contains collision rate, MLP vs RNN preformance and preamble vs collision graphs.
