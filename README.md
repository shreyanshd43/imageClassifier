# Simple AI Image Classification with Convolutional Neural Network #
This Python script demonstrates image classification using a Convolutional Neural Network (CNN) with the CIFAR-10 dataset. The goal is to train a CNN model to accurately classify these images into their respective categories.

# Libraries Used #
- TensorFlow
- NumPy
- Matplotlib

# Code Overview #
**Dataset Loading and Preprocessing:** Load the CIFAR-10 dataset using TensorFlow's datasets module. Preprocess the images by scaling the pixel values between 0 and 1.

**Model Architecture:** Build a CNN model using Keras. The model consists of convolutional layers followed by max-pooling layers. It also includes fully connected (dense) layers for classification.

**Model Compilation:** Compile the model with the Adam optimizer and sparse categorical cross-entropy loss.

**Model Training:** Train the model on the training images and labels. Validate the model using random images.

# Acknowledgements #
This project is inspired by the TensorFlow and NeuralNine tutorials. Images courtesy of Pixabay.
