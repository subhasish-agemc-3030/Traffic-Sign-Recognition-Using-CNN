# Traffic-Sign-Recognition-Using-CNN

A Deep Learning-based Traffic Sign Recognition System that classifies German traffic signs into 43 different categories using a Convolutional Neural Network (CNN).
The project uses Python, TensorFlow/Keras, OpenCV, NumPy, Pandas, and Matplotlib for image processing, model training, evaluation, and visualization.

📌 Project Overview

Traffic sign recognition is an important component of intelligent transportation systems and autonomous driving applications.

In this project, a Convolutional Neural Network (CNN) is trained on the German Traffic Sign Recognition Benchmark (GTSRB) dataset to automatically recognize traffic signs from images.

The system:

. Loads traffic sign images from the GTSRB dataset
. Resizes images to 32 × 32 pixels
. Normalizes pixel values
. Applies image augmentation
. Trains a CNN model
. Classifies images into 43 traffic sign categories
. Evaluates the trained model on unseen test data
. Displays predicted and actual traffic sign labels
