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

- 
# ParkingLot Occupancy Detection

## Overview

This system monitors parking spaces in a video and provides information about the occupancy of each space. It includes functionalities to preprocess video frames, apply image processing techniques, and visualize the results.

## Features

- **Video Input:** The system takes input from a video file (`ParkingLotVideo.mp4`).

- **Parking Space Positions:** The positions of parking spaces are loaded from a pickled file (`Parkinglotpositions`).

- **Image Processing:**
  - Grayscale conversion.
  - Gaussian blur.
  - Adaptive thresholding.
  - Noise removal using median blur.
  - Dilation to fill gaps in parking spaces.

- **Parking Space Occupancy:**
  - The system checks the occupancy of each parking space based on pixel count.
  - Rectangles are drawn around parking spaces on the original image.
  - The count of free spaces is displayed on the image.

## Prerequisites

- Python
- OpenCV
- Numpy
- Cvzone
- Pickle

## Usage

1. Ensure the required dependencies are installed.
   ```bash
   pip install opencv-python numpy cvzone
Run the script.

bash
Copy code
python script_name.py
The processed video frames will be displayed, showing parking space occupancy.

File Descriptions
ParkingLotVideo.mp4: Input video file.
Parkinglotpositions: Pickled file containing parking space positions.



