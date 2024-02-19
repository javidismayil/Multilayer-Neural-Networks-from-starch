<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
</head>
<body>
    <h1>Neural Network Description</h1>
    <p>
        I have implemented a neural network from scratch using Python and Jupyter Notebook. The neural network consists of multiple layers including input, hidden, and output layers. Each neuron in the network applies weights to the input data, followed by an activation function to produce the output.
    </p>
    <p>
        The model architecture includes fully connected layers with ReLU activation functions for hidden layers and softmax activation function for the output layer in the case of classification tasks. I have used stochastic gradient descent (SGD) as the optimization algorithm and categorical cross-entropy as the loss function during training.
    </p>
    <p>
        For training the neural network, I used a labeled dataset consisting of feature vectors and corresponding target labels. The dataset was split into training and validation sets to monitor the model's performance and prevent overfitting. The training process involved iterating over the dataset for multiple epochs, adjusting the model's weights using backpropagation, and evaluating the model's performance on the validation set.
    </p>
    <p>
        After training the neural network, I evaluated its performance on a separate test dataset to assess its generalization ability. The evaluation metrics included accuracy, precision, recall, and F1-score depending on the specific task.
    </p>
    <img src="Architecture-of-multilayer-artificial-neural-network-with-error-backpropagation.png" alt="Neural Network Image" width="500">
    
</body>
</html>
