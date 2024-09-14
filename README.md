# Handwritten-digit-classification
This project is done using  TensorFlow and Keras.
The MNIST dataset is used for this project. It consists of 60,000 training images and 10,000 test images. The dataset can be accessed through TensorFlow/Keras APIs, or you can download it separately.
The model used is a Convolutional Neural Network (CNN) consisting of the following layers:

Input Layer: 28x28 grayscale images.
Convolutional Layers with ReLU activation.
MaxPooling Layers for down-sampling.
Fully Connected (Dense) Layers.
Output Layer: Softmax activation with 10 output nodes (one for each digit class).
After training, the model achieves an accuracy of approximately 97% on the MNIST test dataset. However, this can vary depending on the architecture and hyperparameters used during training.
