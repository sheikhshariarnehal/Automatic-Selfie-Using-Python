# Automatic Selfie Capture with Python

This project demonstrates how to automate the process of taking a selfie using Python, utilizing the `opencv-python` library to access the computer’s webcam. The script captures an image from the webcam, saves it automatically without any user interaction, and cleans up resources when done. This approach is useful for projects involving automated photography or simple image capture tasks.

## Features

- **Library Used**: Utilizes `opencv-python` to access the webcam and capture images.
- **Capture Functionality**: Uses `cv2.VideoCapture(0)` to access the default webcam and `cap.read()` to capture frames.
- **Display and Save**: Displays the captured frame briefly using `cv2.imshow()` and saves it as `selfie.jpg` using `cv2.imwrite()`.
- **User Interaction**: Briefly displays the captured image for a specific duration (e.g., 3 seconds) using `cv2.waitKey()`.
- **Cleanup**: Releases the webcam and closes OpenCV windows with `cap.release()` and `cv2.destroyAllWindows()` after saving the selfie.

## Prerequisites

- **Access to Webcam**: Ensure your computer has a connected webcam. Most laptops have built-in webcams, or you can connect an external webcam via USB.
- **Basic Python Knowledge**: Familiarity with Python programming basics, such as functions and if-statements, will help in understanding and modifying the script.
- **Understanding of OpenCV**: While optional, understanding OpenCV functions (`cv2.VideoCapture`, `cv2.imshow`, `cv2.waitKey`, and `cv2.imwrite`) is beneficial.
- **Python Installation**: Python should be installed on your system. [Download Python](https://python.org).
- **OpenCV Library**: Install `opencv-python` using pip:

  ```bash
  pip install opencv-python
