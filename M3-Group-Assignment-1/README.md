# M4-Group-Assignment-1
Submitted: 07/02/2024

Created by Benjamin, Camilla and Tobias.

## Boston Housing Price Prediction With PyTorch Neural Network

### Task
Build, train, and evaluate neural network models using PyTorch to predict Boston housing prices.

### Dataset
The dataset used for this project is the Boston Housing dataset, which is available in https://www.kaggle.com/datasets/vikrishnan/boston-house-prices/data

### Approach
1. **Feature Selection**: Identify relevant features for predicting housing prices.

2. **Feature Engineering**: Conduct any necessary feature transformations or creations.

3. **Standard ML Preprocessing**: Performing standard preprocessing steps such as MinMax Scaling for the dataset.

4. **Train-Test Split**: Split the dataset into training and testing sets.

5. **Defining Neural Network Architecture**: Design the neural network architecture using PyTorch.

6. **Defining Training Loop**: Set up the training loop for the model.

7. **Training the Model**: Train the neural network on the training data.

8. **Experimenting with Hyperparameters**: Experiment with  5 different variations of hyperparameters including number of layers/neurons, activation functions, epochs, optimizers, and learning rates.

9. **Evaluating the Final Model**: Evaluate the final model on the test data to assess its performance.

### Results
After conducting 5 different variations of hyperparameters (e.g., number of layers/neurons, activation functions, epochs, optimizers, learning rates, etc.). 

It has been evaulated that the best variations from the train data of the architecture of model_net5. It consists of:

- Hyperparameters that consist of 10 epochs and learning_rate of 0.01.
- Parameter with a weight of 50
- 2 hidden layers consisting of: Linear(13,25) + ReLU + Dropout(0.33) and Linear(25,25) + ReLU + Dropout(0.33)
- Output layer consisting of Linear(25,1) and Identity() for a regression problem
- Using Stochastic Gradient Descent as our Optimizer
- Batch size consist of 13

The average loss for epoch 10 showing a loss from train data of 0.0444 which is the best outcome.

In comparison with the test data. The average loss for epoch 10 showing a loss of 0.0382 which is the best outcome.
