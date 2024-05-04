# Maleria_detection_CNN.repo :
- A complex enough CNN model for detection of Maleria.
- This model detect maleria presence based on cellular images provided to it.
# About Notebook :
- <b>This Colab notebook demonstrates how to train a convolutional neural network (CNN) on the CIFAR-10 dataset.<br>Structure of the Neural Network</b>:
    - The CNN consists of two convolutional layers, two max-pooling layers, and one fully-connected layer.
    - The first convolutional layer has 32 filters with a kernel size of 3x3 and uses the ReLU activation function.
    - The second convolutional layer has 64 filters with a kernel size of 3x3 and uses the ReLU activation function.
    - The first max-pooling layer has a pool size of 2x2.
    - The second max-pooling layer has a pool size of 2x2.
    - The fully-connected layer has 64 neurons and uses the ReLU activation function.
    - The output layer has 10 neurons and uses the softmax activation function.
- <b>Dataset</b>:
  - The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 50,000 images for training and 10,000 images for testing.
    The dataset is provided by Keras.
- <b>Training</b>:
  - The model is trained for 10 epochs using the Adam optimizer and the categorical cross-entropy loss function.
  - The training progress is monitored by printing the loss and accuracy on the training and testing sets.
- <b>Evaluation</b>:
  - After training, the model is evaluated on the test set.
  - The accuracy on the test set is printed.
- <b>Additional Information</b>:
  - The code in this notebook can be easily modified to train the CNN on other datasets.
  - The structure of the CNN can also be modified to suit the specific needs of the problem.
