# Fashion Item Classifier using Neural Network

This project implements a neural network in Python using PyTorch to classify grayscale images of fashion items into 10 different categories. The neural network architecture consists of three layers with 784, 512, and 10 nodes respectively. The model uses Rectified Linear Units (ReLU) as activation functions and Cross Entropy Loss for optimization.


## Project Structure

- **model-work.ipynb**: Jupyter notebook containing the Python code for the neural network implementation and testing.
- **network.py**: Directory containing the class that describes the model itself.

## Dataset

The dataset consists of grayscale images of fashion items labeled into 10 categories:

1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

The dataset is split into training and testing sets. The training set is used to train the neural network, while the testing set is used to evaluate its performance.

## Model Architecture

- **Input Layer**: 784 nodes (corresponding to a flattened 28x28 image).
- **Hidden Layer**: 512 nodes with ReLU activation.
- **Output Layer**: 10 nodes with softmax activation. The highest value node indicates the predicted category.

## Training

The model is trained using stochastic gradient descent with Cross Entropy Loss as the loss function. The training process involves iterating over epochs to minimize the loss and improve accuracy.

## Performance

After training, the model achieved an accuracy of 68.3% on the test dataset. This accuracy metric indicates the percentage of correct predictions out of all predictions made.
