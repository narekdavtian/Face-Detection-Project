# Face Detection Project

## Description

This project is a face detection system built using Python and Deep Learning.

The goal of this project is to detect face locations in images and predict bounding box coordinates.

The model takes an image as input and predicts the coordinates of the detected face:

- x0 - left coordinate
- y0 - top coordinate
- x1 - right coordinate
- y1 - bottom coordinate


## Technologies Used

- Python
- NumPy
- Pandas
- OpenCV
- Matplotlib
- TensorFlow / Keras
- Convolutional Neural Network (CNN)


## Dataset

The dataset contains images with annotated face bounding boxes.

Each image has:

- Image width and height
- Face bounding box coordinates
- Image name


## Data Preprocessing

The images were processed using the following steps:

- Converted images to grayscale
- Resized images to 100x100 pixels
- Normalized pixel values between 0 and 1
- Prepared bounding box coordinates as target values


## Model Architecture

The model is a Convolutional Neural Network (CNN).

Architecture:

- Conv2D layers for feature extraction
- MaxPooling layers for dimensionality reduction
- Flatten layer
- Dense layers
- Output layer with 4 values for bounding box prediction


## Prediction

The model predicts face coordinates on new images and draws the bounding box around the detected face.


## Project Structure

Face-Detection-Project/
│
├── Face_Detection_project.ipynb
├── faces.csv
├── images/
├── README.md
└── .gitignore




## How to Run

1. Clone the repository:
https://github.com/narekdavtian/Face-Detection-Project.git


2. Install dependencies:
pip install -r requirements.txt


3. Open the notebook:
Face_Detection_project.ipynb



## Result

The trained CNN model can detect face positions and visualize predicted bounding boxes on images.