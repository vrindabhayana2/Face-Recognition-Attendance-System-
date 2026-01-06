# Face-Recognition-Attendance-System-
## 📌 Project Overview
This project is a **Face Recognition based Attendance Management System** developed using Python.
It automatically detects and recognizes student faces using a webcam and marks attendance without manual intervention.

The system is designed to reduce proxy attendance and save time in classrooms.

---

## 🛠️ Technologies Used
- Python
- OpenCV
- Haar Cascade Classifier
- NumPy
- Pandas

---

## ⚙️ Features
- Automatic face detection using webcam
- Face recognition based on trained images
- Automatic attendance marking
- Manual attendance option
- Attendance stored in CSV format
- Simple and user-friendly interface

---
## ⚙️ Prerequisites
- Python 3.7+
- Install OpenCV, face_recognition, numpy, pandas

## 📁 Project Structure
Face-Recognition-Attendance-System/
 Attendance/                # Stores attendance records
 StudentDetails/            # Student information (sample data)
 TrainingImageLabel/        # Trained images and labels
 UI_Image/                  # UI related images
 Project Snap/              # Project screenshots
 AMS.py                     # Main application file
 attendance.py              # Attendance logic
automaticAttendance.py     # Automatic attendance module
 takeImage.py               # Capture student images
 takemanually.py            # Manual attendance option
 trainImage.py              # Train face recognition model
 show_attendance.py         # Display attendance records
 test.py                    # Testing file
 haarcascade_frontalface_default.xml
 haarcascade_frontalface_alt.xml
 requirements.txt           # Project dependencies
README.md

---

## ▶️ How to Run the Project
### Step 1: Install Dependencies
pip install -r requirements.txt

### Step 2: Run the Project
python AMS.py
