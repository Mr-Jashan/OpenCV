# The approach used for this Python project is as follows :

Step 1 – Take image as input from a camera.

Step 2 – Detect the face in the image and create a Region of Interest (ROI).

Step 3 – Detect the eyes from ROI and feed it to the classifier.

Step 4 – Classifier will categorize whether eyes are open or closed.

Step 5 – Calculate score to check whether the person is drowsy.


# Dataset
Download the dataset: Driver Drowsiness Dataset

# The Model Architecture
The CNN model architecture consists of the following layers:

Convolutional layer; 32 nodes, kernel size 3

Convolutional layer; 32 nodes, kernel size 3

Convolutional layer; 64 nodes, kernel size 3

Fully connected layer; 128 nodes

# Project Prerequisites
The requirement for this Python project is a webcam through which we will capture images. You need to have Python (3.6 version recommended) installed on your system, then using pip, you can install the necessary packages.

OpenCV – pip install opencv-python (face and eye detection).

TensorFlow – pip install tensorflow (keras uses TensorFlow as backend).

Keras – pip install keras (to build our classification model).

Pygame – pip install pygame (to play alarm sound).

# Input/Output

![image](https://user-images.githubusercontent.com/72308753/213863784-590d2456-e44b-4a1f-bca9-5f72549a98e2.png)

![image](https://user-images.githubusercontent.com/72308753/213863811-647333d2-6d84-44eb-8f54-f421c8699d06.png)

![image](https://user-images.githubusercontent.com/72308753/213863907-52f51ed5-b250-4ac5-a820-f6a14db1779c.png)
