# Creating-a-Robust-Facial-Recognition-System-using-Python-and-Tensorflow
face tracking task using deep learning

1-Captures images from the webcam and saves them to the "data/images" directory.

2-Applies data augmentation techniques using the Albumentations library to create additional images for training a deep learning model for face tracking.

3-Loads images and corresponding labels (bounding box coordinates and class labels) from the "aug_data" directory.

4-Builds a custom face tracking model using VGG16 as the base model and adds classification and regression layers on top.

5-Compiles the custom face tracking model with custom loss functions for classification and regression.

6-Trains the model using the loaded datasets.

7-Plots training and validation loss during the training process.

8-Runs real-time face tracking using the trained model on webcam feed and displays the webcam feed with detected faces.

