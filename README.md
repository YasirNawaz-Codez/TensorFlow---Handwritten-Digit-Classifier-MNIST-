# TensorFlow - Handwritten Digit Classifier (MNIST)

This project demonstrates handwritten digit classification using a basic neural network trained on the MNIST dataset. A simple network with only input and output layers is initially implemented. A hidden layer is then added to the network to observe the resulting performance improvement in recognizing handwritten digits.

## Dataset

The MNIST dataset is a large database of handwritten digits that is commonly used for training various image processing systems and machine learning models. It consists of 60,000 training images and 10,000 testing images, each representing a grayscale image of a handwritten digit from 0 to 9.

## Model Architecture

Two neural network architectures are implemented in this project:

1. **Simple Network:** This network consists of only input and output layers. The input layer has 784 neurons (representing the 28x28 pixels of the MNIST images), and the output layer has 10 neurons (representing the 10 possible digit classes).

2. **Hidden Layer Network:** This network includes a hidden layer with 100 neurons between the input and output layers. The hidden layer uses the ReLU activation function, while the output layer uses the sigmoid activation function.

## Results

The models were trained on the MNIST training dataset and evaluated on the MNIST testing dataset. The following accuracies were achieved:

- Simple Network: 92.51%
- Hidden Layer Network: 97.67%

The addition of a hidden layer significantly improved the model's performance in recognizing handwritten digits.

## Usage

To run this project, you will need to have TensorFlow and Keras installed. You can then clone this repository and execute the Python script provided.

## Conclusion

This project demonstrates the effectiveness of neural networks in classifying handwritten digits. The use of a hidden layer significantly improves the model's accuracy. This project can be used as a starting point for further exploration of neural networks and their applications in image recognition tasks.

