# Traffic-Sign-Recognition-Using-CNN

A Deep Learning-based Traffic Sign Recognition System that classifies German traffic signs into 43 different categories using a Convolutional Neural Network (CNN).
The project uses Python, TensorFlow/Keras, OpenCV, NumPy, Pandas, and Matplotlib for image processing, model training, evaluation, and visualization.

📌 **Project Overview**

Traffic sign recognition is an important component of intelligent transportation systems and autonomous driving applications.

In this project, a Convolutional Neural Network (CNN) is trained on the German Traffic Sign Recognition Benchmark (GTSRB) dataset to automatically recognize traffic signs from images.

The system:

&bull; Loads traffic sign images from the GTSRB dataset <br>
&bull; Resizes images to 32 × 32 pixels <br>
&bull; Normalizes pixel values <br>
&bull; Applies image augmentation <br>
&bull; Trains a CNN model <br>
&bull; Classifies images into 43 traffic sign categories <br>
&bull; Evaluates the trained model on unseen test data <br>
&bull; Displays predicted and actual traffic sign labels <br>

🎯 **Objectives**

The main objectives of this project are:

1. To develop a traffic sign classification system using Deep Learning.<br>
2. To preprocess and normalize traffic sign images. <br>
3. To use CNNs for automatic feature extraction and classification. <br>
4. To improve model generalization using image augmentation. <br>
5. To classify German traffic signs into 43 different categories.<br>
6. To evaluate the performance of the trained model using accuracy and loss. <br>
7. To visualize predictions made by the trained CNN model. <br>

🛠️ Technologies Used
<table>
<tr>
<td>

###  Technology
- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Kaggle

</td>
<td>

### Purpose
- Programming language
- Deep learning framework
- CNN model development
- Image processing
- Numerical operations
- Dataset handling
- Visualization
- Train-test splitting
- Dataset/training environment
</td>
</tr>
</table>


📂 **Dataset**

This project uses the German Traffic Sign Recognition Benchmark (GTSRB) dataset.

The dataset contains images belonging to 43 different traffic sign classes.

&bull;  Dataset characteristics<br>
&bull;  Number of classes: 43<br>
&bull;  Image type: Traffic sign images<br>
&bull;  Input size: 32 × 32 × 3<br>
&bull;  Color format: RGB/BGR image data<br>
&bull;  Task: Multi-class image classification<br>

The dataset contains traffic signs such as:

&bull;  Speed limits<br>
&bull;  Stop<br>
&bull;  No entry<br>
&bull;  Yield<br>
&bull;  Priority road<br>
&bull;  No passing<br>
&bull;  Road work<br>
&bull;  Pedestrian crossing<br>
&bull;  Traffic signals<br>
&bull;  Roundabout<br>
&bull;  Keep left/right<br>
&bull;  Dangerous curves<br>
&bull;  Slippery road <br>
&bull;  And many more <br>


🧠 **CNN Architecture**

The project uses a custom Convolutional Neural Network.

**Model Architecture**
Input Image
32 × 32 × 3
     ↓
Conv2D
32 Filters, 3 × 3
     ↓
MaxPooling
     ↓
Conv2D
64 Filters, 3 × 3
     ↓
MaxPooling
     ↓
Conv2D
128 Filters, 3 × 3
     ↓
MaxPooling
     ↓
Flatten
     ↓
Dense
256 Neurons
     ↓
Dropout
0.5
     ↓
Dense
43 Neurons
     ↓
Softmax
     ↓
Traffic Sign Class
