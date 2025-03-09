# Machine_Learning_with_CFD

![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
	![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

A part of research during Master of Philosophy candidature in University of New South Wales. 
Refer to Chapter 4 from [thesis](https://doi.org/10.26190/unsworks/30911) for details. 

Features:
  - Data visualisation & pre-processing
  - ML model development with supervised learning
    - Linear
    - Polynomial
    - Ridge & LASSO
    - Support Vector Regressor
    - Decision Tree & Random Forest
    - Gradient Boosting & XGBoost
    - Neural Network
  - Hyperparameter tuning with cross-validations
  - Evaluation of results with
      - R-Squared
      - Mean Absolute Error
      - Mean Absolute Percentage Error
      - Mean Squared Error

## Research Topic

In this research, various 3D models of metal hydride hydrogen storage reactors with different internal helical coil parameters were developed and solved by Computational Fluid Dynamics (CFD). Different helical coil parameters affect the hydrogen absorption time. Therefore, this study firstly collects data from CFD, then predicts the hydrogen absorption time of a metal hydride hydrogen reactor given different helical coil parameters.

![image](https://github.com/user-attachments/assets/38f6a6e4-ee91-443c-b128-8562cb241bb6)


## Overall Methodology

![image](https://github.com/user-attachments/assets/430ea1b6-a64d-4337-9905-333f6625f856)


The raw data file is located at [/Machine_Learning_with_CFD/dataset.csv](https://github.com/siwoo-jung/Machine_Learning_with_CFD/blob/main/dataset.csv)

## Python code

The python code is located at [/Machine_Learning_with_CFD/code.ipynb](https://github.com/siwoo-jung/Machine_Learning_with_CFD/blob/main/code.ipynb)

## Conclusion

- All machine learning models in this study recorded R2 higher than 0.9, MAE less than 30 seconds, and MAPE less than 5%, which suggest that these models can predict the hydrogen absorption time well, given the different coil design parameters
- Classical regression models, such as polynomial, Ridge and LASSO, recorded 0.99 R2, 10 seconds of MAE and 1.7% of MAPE, which demonstrate they perform better than tree-based models or ANN, due to relatively simple relationships in input datasets, regularization terms in these models, and the nature of tree-based models being prone to capturing noise in the datasets

![image](https://github.com/user-attachments/assets/214d29e0-28db-42a2-a76c-dcab6dc21390)



