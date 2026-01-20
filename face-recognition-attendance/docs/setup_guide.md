# Setup Guide – Face Recognition Attendance System

This guide explains how to set up, install, and run the Face Recognition
Attendance System on a local machine.

---

## 1. System Requirements

### Hardware
- PC / Laptop
- Working webcam (internal or external)
- Minimum 4 GB RAM (8 GB recommended)

### Software
- Operating System: Windows / Linux / macOS
- Python version: **3.8 or higher**
- Internet connection (for initial package installation)

---

## 2. Project Folder Structure

Ensure the project directory is organized as follows:

face-recognition-attendance/
├── src/
│ └── face_attendance.py
├── dataset/
│ ├── student1.jpg
│ ├── student2.jpg
│ └── README.md
├── docs/
│ └── setup_guide.md
├── requirements.txt
└── README.md


---

## 3. Python Environment Setup (Recommended)

Create a virtual environment to avoid dependency conflicts.

### Windows
```bash
python -m venv venv
venv\Scripts\activate
