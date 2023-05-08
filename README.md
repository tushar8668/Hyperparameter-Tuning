# Hyperparameter-Tuning
- Randomised Seach CV
  - Randomized Search CV selects hyperparameter values randomly from a specified range of values, and then performs cross-validation to evaluate the performance of the model with these hyperparameters. The process is repeated a specified number of times, with different randomly selected hyperparameter values each time. The results of each cross-validation are then aggregated to provide an estimate of the model's performance with different hyperparameter values.
  - The advantage of Randomized Search CV over Grid Search is that it can search a much larger hyperparameter space in the same amount of time. This is because it does not exhaustively search over all possible combinations of hyperparameters, but rather selects a random subset of hyperparameters to evaluate. This can be especially useful when the number of hyperparameters is large or the hyperparameter space is complex.

- GridSearch CV
  - Grid Search CV is a technique used to find the best combination of hyperparameters for a machine learning model.
  - When we use Grid Search CV, we first define a grid of hyperparameters to search through. This grid contains a list of all possible combinations of hyperparameters we want to tune. For example, we may define a grid with different values for the learning rate, number of hidden layers, and number of neurons in each layer.
  - Grid Search CV then exhaustively searches through this grid, training and evaluating the model for each combination of hyperparameters in the grid. It uses cross-validation to evaluate the performance of each model on multiple splits of the data.
  - The final result of the Grid Search CV is the best combination of hyperparameters that gives the highest performance on the validation set. This combination can be used to train the final model on the entire dataset.
