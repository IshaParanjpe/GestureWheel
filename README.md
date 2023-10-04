# Gesture Wheel - Real-Time Hand Gesture Detection

Gesture Wheel is a computer vision project designed to recognize hand gestures in real-time using Convolutional Neural Networks (CNNs). With this application, users can interact with their computer using hand gestures captured through their camera. You can control various actions by making specific hand gestures in front of the camera.

## Table of Contents
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Training the Model](#training-the-model)
  - [Dataset](#dataset)
- [How to Use](#how-to-use)
- [Conclusion](#conclusion)

## Getting Started

### Prerequisites

Before running the Gesture Wheel application, make sure you have the following prerequisites installed:

- Python 3.6 or higher
- TensorFlow 2.0 or higher
- OpenCV 4.0 or higher
- NumPy

## Usage

1. Clone this repository to your local machine.
2. Install the required Python packages mentioned in the prerequisites.
3. Run the application using the following command:

   ```bash
   python gesture_wheel.py
   ```

4. Control your computer with the following hand gestures:
   - Volume Up: Thumbs up
   - Volume Down: Thumbs down
   - Place a Call: Thumb and Pinky
   - Stop Music: Stop Sign
   - Play Rock Song: Yo Sign
   - Next: Index and Thumb

## Training the Model

### Dataset

The model was trained on the Hand Gesture Recognition Database, which contains ten different hand gestures performed by ten different users.

To train the model on a custom dataset, refer to the provided documentation in the [training section](training/README.md).

## How to Use

1. Run the Gesture Wheel application, as explained in the [Usage](#usage) section.
2. Ensure that your camera is correctly positioned and can capture your hand gestures.
3. Make one of the specified hand gestures in front of the camera to control various actions.
4. The application will recognize your gestures in real-time and perform the corresponding actions.

## Conclusion

Gesture Wheel showcases the power of computer vision and machine learning in creating intuitive and interactive interfaces. By recognizing hand gestures in real-time, this project simplifies computer interaction for various tasks. The provided README file helps you set up and use the application, and it also guides you on how to train the model with your custom dataset.

Feel free to contribute to and improve this project to make it even more versatile and user-friendly.
```
