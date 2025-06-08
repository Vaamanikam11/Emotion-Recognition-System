# Emotion-Recognition-System

This project is an AI-powered emotion recognition system that uses computer vision and deep learning to detect and classify human emotions in real time via a webcam feed.

## 💡 Features
- Real-time facial emotion detection using a webcam
- Trained using transfer learning with a pre-trained VGG model
- Classifies emotions like Happy, Sad, Angry, Neutral, etc.
- Utilizes Haar Cascade for face detection
- Trained with Keras and TensorFlow backend

## 🛠 Tech Stack
- Python, OpenCV, Keras, TensorFlow
- Jupyter Notebook
- Haarcascade Frontal Face XML
- CNN with VGG16 for feature extraction

## 📂 Files
- `train.py`: Trains the CNN on emotion datasets
- `Test.py`: Launches the real-time emotion detection using webcam
- `model.h5`: Trained model weights
- `haarcascade_frontalface_default.xml`: Used for face detection

## 🚀 How to Run
1. Clone the repo
2. Run `Test.py` in an environment with a working camera
3. Emotion label appears on detected face in real time

## 📸 Output
Real-time annotated video stream with emotion labels on faces

---
