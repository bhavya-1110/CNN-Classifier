<h2 align="center"> CAT v/s DOG CNN CLASSIFIER </h2>
This is a deep learning project that involves building a convolutional neural network (CNN) classifier to distinguish between cats and dogs in images. The classifier is trained using a dataset of thousands of images of cats and dogs, and then tested on a separate set of images to measure its accuracy.

<h5> DATASET </h5>
The dataset used for this project consists of 40,000 images of cats and dogs, with 20,000 images of each class. The images are in JPEG format and are of different sizes. The dataset is split into a training set and a testing set, with 30,000 images used for training and 10,000 images used for testing.

<h5> MODEL ARCHITECTURE </h5>
The CNN classifier is built using Keras, a high-level neural networks API written in Python. The architecture of the model consists of four convolutional layers with max pooling. The activation function used in the convolutional layers is ReLU, and the output layer uses the sigmoid function to output a probability between 0 and 1 for each class.

<h5> TRAINING </h5>
The model is trained using the Adam optimizer and binary crossentropy as the loss function. The training is done in batches of 700 images and is run for 10 epochs. The training accuracy and validation accuracy are recorded after each epoch, and the model is saved after the epoch with the highest validation accuracy.

<h5> TESTING </h5>
The trained model is tested on the testing set. The model accuracy and model loss are also plotted to visualize the classification performance of the model.

<h5> CONCLUSION </h5>
This project demonstrates the effectiveness of convolutional neural networks for image classification tasks. The CNN classifier built in this project achieves an accuracy of over 80% on the testing set, which is a significant improvement over the performance of traditional machine learning algorithms on this dataset. This project can be extended by using more advanced CNN architectures, exploring data augmentation techniques, and experimenting with different hyperparameters.
