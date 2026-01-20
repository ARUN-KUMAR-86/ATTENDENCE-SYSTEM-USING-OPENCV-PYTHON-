# ATTENDENCE-SYSTEM-USING-OPENCV-PYTHON-
A Python-based Face Recognition Attendance System using OpenCV and face_recognition. The system identifies registered faces via webcam, marks attendance with date and time in an Excel file, prevents duplicate entries per day, and provides a real-time visual interface for automated, contactless attendance management.

https://drive.google.com/file/d/1VctMuhSJfGLmipmBR2P6Ys_NSAz1uZNo/view?usp=drive_link
https://drive.google.com/file/d/1BB1MZ1vwBJxP8dEGkCGIkZxxPtMkcG2v/view?usp=drive_link

# Face Recognition Attendance System

This project implements a real-time face recognition-based attendance
system using Python, OpenCV, and the face_recognition library.

## Features
- Real-time face detection via webcam
- Automatic attendance marking
- Excel-based attendance log
- Duplicate prevention per day

## Project Architecture
Camera → Face Detection → Face Encoding → Matching → Excel Attendance

## Folder Structure
- src/        : Python source code
- dataset/    : Face images (one per person)
- output/     : Attendance records
- docs/       : Documentation and diagrams

## How to Run
1. Place images in `dataset/`
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
## Run
- python src/face_attendance.py
