# Deep-Neural-Network-for-MNIST-Classification

The goal of this work is to write a program capable of detecting which digit is written based on the MNIST dataset. The MNIST dataset refers to handwritten digit recognition and provides 70000 images (28x28 pixels) of handwritten digits (1 digit per image). This classification is a problem with 10 classes since we have 10 digits (0,1,2,3,4,5,6,7,8,9).


After building the network with only two hidden layers and 50 units per hidden layer (see "Deep Neural Network for MNIST Classification_Sofiane_Ikkour" code), I tuned some hyperparameters and tried several combinations. The final tuning ended up improving the accuracy from 96.92% to ~98%.

Below are some details about the different tries it took to reach the final result:

- The width of the algorithm: the size of both hidden layers was changed to 200.
- The depth of the algorithm: the number of the hidden layers was changed to 4.
- Activation functions: the sigmoid activation function was applied to every hidden layer. The softmax activation function was applied to the output layer.
- Learning Rate: 0.0001, 0.02.
- Batch size adjusted: 1 (that's the SGD).
- Number of epochs: 5, 8, 10.

The final combination I tried gave an accuracy of about 98%.

Hyperparameter optimiztion:

Many hyperparameter adjustements have been applied in order to improve the accuracy of the model. I chose the following hyperparameters:

batch_size = 150
hidden units = 500
hidden layers = 5
Number of epochs = 10
The accuracy improved from 96.92% to ~98%. This result is remarkably good given the number of hidden layers and the number of units used. This can be improved even further.

Although this is a remarkable result, there is still room for improvement and an accuracy of 99% is possible with the right combination of hyperparameters.

Note: this code was written on Google Colab.
