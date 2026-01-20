# Dataset Information – Face Recognition Attendance System

This project automatically marks attendance by recognizing a person’s face using a webcam.
It compares the live camera image with stored face photos to identify the person.
When a known face is detected, the system saves the name, date, and time in an Excel file.
This removes the need for manual attendance and reduces errors or proxy attendance.
This folder contains sample face images used for training and testing
the face recognition-based attendance system.

---

## Image Naming Convention

- Each image file name represents the **person's name**
- The file name (without extension) is used as the attendance label

### Example
student1.jpg → Name recorded as "student1"
student2.jpg → Name recorded as "student2"


---

## Image Requirements

- One clear face per image
- Front-facing or near front-facing pose
- Good lighting conditions
- No masks or heavy occlusions
- Recommended resolution: **≥ 300 × 300 pixels**

---

## Dataset Guidelines

- Store only **sample or AI-generated images**
- Do NOT upload real student photos in public repositories
- For best accuracy, use images with neutral expressions

---

## Supported Formats

- `.jpg`
- `.jpeg`
- `.png`

---

## Folder Usage

- Images in this folder are loaded at program start
- Face encodings are generated once and stored in memory
- If an image contains no detectable face, it is skipped automatically

---

## Privacy & Ethics Notice

This project is intended for **educational and demonstration purposes only**.
Ensure compliance with privacy laws and institutional guidelines before
using real facial data.

---

## Example Dataset Structure

