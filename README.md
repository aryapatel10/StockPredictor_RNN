# StockPredictor_RNN
Leveraging Recurrent Neural Networks (RNNs) to predict stock prices based on historical data.
### Introduction
StockPredict_RNN is a deep learning project that aims to predict stock prices using historical data for open, high, low, close, and volume. The project utilizes PyTorch for building and training the RNN model, and Scikit-learn for data preprocessing and evaluation.

### Dataset
The dataset should include columns for timestamp, 'open', 'high', 'low', 'close', and 'volume'.

### Model Architecture
The model architecture consists of a simple Recurrent Neural Network (RNN) with:
Input layer size: 5 (features: open, high, low, close, volume)
Hidden layer size: 100
Output layer size: 5 (predicting open, high, low, close, volume for the next step)

### Training and Validation
The model is trained for 10 epochs using Mean Squared Error (MSE) loss and Adam optimizer. The training process prints the loss for each epoch.
Validation is performed by comparing the predicted values with the actual values, and the validation loss is computed.

### Results
The model's performance is evaluated using the Mean Squared Error (MSE) metric. The loss value indicates how well the model's predictions match the true values.

### Contributing
Contributions are welcome! Please feel free to submit a Pull Request.


