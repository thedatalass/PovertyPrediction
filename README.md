## World Bank Poverty Prediction

__Summary__: Artificial neural networks can be used to predict which features in a dataset predict a household's poverty.

__Data__: 2018 World Bank household-level survey training data with 8200 observations, 343 features (reduced to 4 with PCA) and 1 target variable (poverty).

__Results__: k-Nearest Neighbor precision 0.52, recall 0.52, F1 score 0.52; stochastic gradient descent precision 0.52, recall 0.52, F1 score 0.52, mean log loss 15.68; multilayer perceptron 114 neurons, 2 layers, and lbfgs solver precision 0.85, recall 0.85, F1 score 0.85, mean log loss 12.22,; multilayer perceptron 342 neurons, 4 layers, and lgfgs solver precision 1.0, recall 1.0, f1 score 1.0, mean log loss 9.99 e-16).


## IDB Costa Rican Household Poverty Level Prediction

__Summary__: Machine learning classification techniques can be used to predict which features in a dataset predict a household's poverty.

__Data__: 2018 International Development Bank household-level survey training data with 9557 observations, 143 features and 1 target variable (poverty level).

__Results__: Random Forest had macro F1 score = 0.9976
