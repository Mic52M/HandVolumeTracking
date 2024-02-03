# Gesture Volume Control

## Description
Gesture Volume Control is an innovative project that utilizes computer vision and machine learning to allow users to control their computer's volume level with simple hand gestures. By leveraging the capabilities of OpenCV for image processing and MediaPipe for advanced hand tracking, this application can detect the distance between the user's thumb and index finger, adjusting the volume in real-time. This hands-free approach to volume control offers a seamless and intuitive user experience, ideal for presentations, multimedia consumption, or any scenario where traditional volume adjustment methods are not practical.

## Dependencies

To run this project, you will need the following software and libraries:

### Pre-requisites
- Python 3.8 or higher
- OpenCV library (`cv2`)
- MediaPipe
- NumPy
- An operating system with support for `amixer` (typically Linux)

### Installation

First, ensure you have Python installed on your machine. Then, you can install the required libraries using pip:

```bash
pip install opencv-python
pip install mediapipe
pip install numpy
```


## Usage

To control your computer's volume using hand gestures, follow these steps:

- **Allow Camera Access:** Ensure your computer's webcam is enabled and permitted to be used by the application. The program will automatically access the webcam upon startup.

- **Perform Hand Gestures:** Place your hand in view of the camera. The application recognizes the distance between your thumb and index finger. Adjust this distance to control the volume:
  - **Decrease Volume:** Bring your thumb and index finger closer together.
  - **Increase Volume:** Move your thumb and index finger further apart.

- **Exit the Application:** To exit, simply press the 'ESC' key while the application window is active.

### Notes

- Ensure good lighting for the camera to accurately detect your hand gestures.
- The application currently supports single-hand gestures. Make sure one hand is clearly visible to the camera for precise volume control.

## Contributing

Contributions to the Gesture Volume Control project are warmly welcomed. If you have suggestions for improvements, bug reports, or new features, please follow these steps:

- **Fork the Repository:** Create a fork of the main project on GitHub.
- **Create a Feature Branch:** Work on your new feature or fix in a separate branch named after the improvement.
- **Commit Your Changes:** Make sure your code adheres to the project's existing style and is well commented.
- **Submit a Pull Request:** Push your branch to your fork and open a pull request against the main project.



