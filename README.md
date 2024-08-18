# Machine_Learning_with_CFD
A part of research during Master of Philosophy candidature in University of New South Wales. 

Refer to Chapter 4 from [thesis](https://github.com/siwoo-jung/Machine_Learning_with_CFD/blob/main/thesis.pdf) for details. **Note that this is a draft and currently awaiting the supervisor's approval for the final submission, which will be submitted to the University of New South Wales by 9th of September 2024.**

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



