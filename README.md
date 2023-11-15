# COMPUTER-VISION

# Facial Expression Detection

## Overview

This project focuses on detecting facial expressions in images using a pre-trained deep learning model. It utilizes a Convolutional Neural Network (CNN) to predict the emotional state of individuals in the given images.

## Features

- Facial expression detection for seven emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral.
- Integration with pre-trained model and OpenCV for face detection.
- Displaying detected faces with predicted emotions on the input images.

## Prerequisites

- Python 3.x
- TensorFlow (`pip install tensorflow`)
- OpenCV (`pip install opencv-python`)

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/JoehIreri/facial-expression-detection.git
    cd facial-expression-detection
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the detection script:

4. View the results:

    The script will display the input image with detected faces and their predicted emotions.

## Model Details

- The emotion detection model is based on a CNN architecture and is pre-trained on a dataset containing facial expressions.

## Configuration

- **face_cascade_path:** The path to the Haar Cascade classifier XML file for face detection.

# Parking Lot Occupancy Detection

## Overview

This project aims to detect the occupancy status of a parking lot by analyzing images or video frames from surveillance cameras. The system determines whether parking spaces are empty or occupied, helping users find available parking spots more efficiently.

## Features

- Parking lot occupancy status detection.
- Visualization of detected contours on the parking lot image.
- Easy integration with surveillance camera feeds.

## Prerequisites

- Python 3.x
- OpenCV (`pip install opencv-python`)
- Numpy (`pip install numpy`)

## Usage

1. Clone the repository:

2. Install dependencies:

3. Run the detection script:

4. View the results:

    The script will display whether the parking lot is empty or occupied, and it will show the original image with drawn contours indicating detected objects.

## Configuration

- **occupancy_threshold:** Adjust this threshold to control the sensitivity of occupancy detection.

