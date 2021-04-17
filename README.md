# [Handwritten-Digit-Recognition](https://github.com/kuluruvineeth/Handwritten-Digit-Recognition/blob/main/Handwritten%20Digit%20Recognition.ipynb)

# Handwritten Digit Recognition Dataset
* The dataset was constructed from a number of scanned document datasets available from the National Institute of Standards and Technology(NIST).
* Each image is a 28*28 pixel square(784 pixels total).
* A standard split of the dataset is used to evaluate and compare models where 60,000 images are used to train a model and a separate set of 10,000 images are used to test it.
* 10 classes(0 to 9) to predict.
* Sample dits
* ![digits](https://github.com/kuluruvineeth/Handwritten-Digit-Recognition/blob/main/digits.png)
* * Model Strcuture
![image1](https://github.com/kuluruvineeth/Handwritten-Digit-Recognition/blob/main/baseline_model.png)

# Simple Convolutional Neural Network for MNIST
## structure of CNN
1. The first hidden layer is a convolutional layer called a **Convolution2D**.The layer has 32 feature maps with size of 5*5 and a rectifier activation function.Expecting input images.
2. pooling layer called **MaxPooling2D**.pool size is 2*2.
3. **Dropout Regularization**,it is configured to randomly exclude 20% of neurons in the layer in order to reduce overfitting.
4. **Flatten** converts the 2D matrix data to a vector.It allows the output to be processed by standard fully connected layers.
5. **fully connected layer** with 128 neurons and a rectifier activation function.
6. **Output layer** has 10 neurons for 10 classes and softmax function to output probability-like predictions for each class.
![image2](https://github.com/kuluruvineeth/Handwritten-Digit-Recognition/blob/main/CNN_small.png)

# Larger Convolutional Neural Network
![image3](https://github.com/kuluruvineeth/Handwritten-Digit-Recognition/blob/main/CNN_large.png)


