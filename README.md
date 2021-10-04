# RealTime_Face_Detector
Real-time face detector with Python, TensorFlow/Keras and OpenCV. This is program, that do real-time face detection on webcam image and also can distinguish me from other people.
## Setup 
To run this code, you must have tensorflow and opencv libraries installed.</br>
You should create virtual environment, activate it and run pip install -r requirements.txt
## Project Structure
The project has following structure:</br>
* data_augmentation.ipynb
* classifier_model_comparison.ipynb
* RealTimeDetector.ipynb
* README.md
* requirement.txt

Now let's talk about the code files - jupyter notebooks.</br>
* data_augmentation.ipynb file creates an augmented dataset from an initial one and provides some information about the dataset.
* classifier_model_comparison.ipynb file contains code to train and test five different models. You can use it as an example to build your own classifier.
* RealTimeDetector.ipynb file uses the OpenCV library and turns the classifier into a real-time detector.
