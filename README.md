# Face-Emotion-Detection-Using-Raspberry-Pi

This is a real-time emotion detection application using OpenCV and Keras. It detects faces in a video stream and predicts the emotions of the detected faces.

## Prerequisites

Before running the application, make sure you have the following dependencies installed:

- Python (>=3.6)
- OpenCV (cv2)
- Keras
- NumPy
- Tkinter (for GUI)

You can install the required dependencies using pip:

```bash
pip install opencv-python keras numpy

## Notes
The application uses a pre-trained face detection model (haarcascade_frontalface_default.xml) and an emotion detection model (model.h5). Make sure these files are present in the specified directories.
Emotions detected: Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise.
Make sure your webcam is connected and functional before running the application.
