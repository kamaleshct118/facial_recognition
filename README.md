# Facial Recognition Project

## Overview
This project implements a facial recognition system using OpenCV and Python. It consists of the following files:

1. **face_recognition.py**: The main script handling facial recognition.
2. **recognition.py**: Script for identifying faces.
3. **haarcascade_frontalface_default.xml**: A pre-trained Haar cascade model for face detection.
4. **.idea/**: Configuration files for the IDE.

## Features
- Capture and store images with labeled folders.
- Identify and recognize faces in real-time.
- Uses OpenCV for image processing.

## Prerequisites
Make sure you have the following installed:

- Python 3.x
- OpenCV (`cv2`)
- NumPy

Install dependencies using:
```bash
pip install opencv-python numpy
```

## Usage

### Step 1: Run Face Recognition Script
Run the main script to start face recognition:
```bash
python face_recognition.py
```

### Step 2: Run Recognition Script
Run the recognizer script to identify faces:
```bash
python recognition.py
```

## Folder Structure
```
FacialRecognition/
│── face_recognition.py
│── recognition.py
│── haarcascade_frontalface_default.xml
│── .idea/
│── README.md
```

## Future Improvements
- Implement deep learning-based face recognition.
- Enhance accuracy with additional preprocessing.

## License
This project is open-source under the MIT License.

