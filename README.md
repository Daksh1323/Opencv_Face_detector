# Face Detection Using OpenCV and Python

## 📌 Project Overview
This project demonstrates real-time **Face Detection** using **OpenCV and Python**. The system detects human faces from a live webcam feed and highlights them using rectangular bounding boxes. It focuses only on detecting faces and does not perform face recognition or identity verification.

The project uses a **Haar Cascade Classifier**, which is a pre-trained machine learning model provided by OpenCV. Since the model is already trained, no dataset collection or training process is required, making this project ideal for beginners in computer vision.

---

## 🎯 Objectives
- To understand the basics of computer vision
- To detect human faces in real time using a webcam
- To learn how Haar Cascade classifiers work
- To gain hands-on experience with OpenCV in Python

---

## 🛠️ Technologies Used
- Python 3
- OpenCV
- Haar Cascade Classifier
- Webcam (for live video input)

---

## 📁 Project Structure
face detector/<br>
│<br>
├── face_detector_opencv.py<br>
├── haarcascade_frontalface_default.xml<br>
└── README.md<br>


## ⚙️ Installation & Setup

1. Install OpenCV:
pip install opencv-python

Download the Haar Cascade file:

haarcascade_frontalface_default.xml

Place it in the same folder as the Python file

Run the program:
python face_detector_opencv.py
##  🚀 How It Works
The webcam captures live video frames

Frames are converted to grayscale

The Haar Cascade classifier detects face regions

Rectangles are drawn around detected faces in real time

## 📌 Applications
Security and surveillance systems

Attendance monitoring

Smart camera applications

Human-computer interaction

## 🔮 Future Scope
Face recognition

Smile and eye detection

Emotion detection

Attendance system using face recognition

##  👤 Author
Daksh

## ⭐ Acknowledgements
OpenCV Official Documentation
Open-source computer vision community
