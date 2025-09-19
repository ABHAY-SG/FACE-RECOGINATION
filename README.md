# HACKATHON PROJECT

# Face Recognition Attendance System

A Python-based attendance system that uses **face recognition** to automatically mark attendance, record entry time, and save details into an Excel sheet. The system also provides **voice feedback** when a person’s attendance is marked.

## ✨ Features
- Detects and recognizes faces in real-time using a webcam.
- Stores known faces from a training folder (`demo_photos/`).
- Marks attendance with **Name, Date, Time, and Status** (On Time / Late).
- Prevents duplicate entries for the same day.
- Saves attendance records into `attendance.xlsx` (new sheet created daily).
- Voice announcement using **pyttsx3**.
- Shows total number of people present on the live video feed.

## 📂 Project Structure
project/
│── demo_photos/          # Folder containing demo  images
│── attendance.xlsx       # Excel file (auto-created)
│── app.py               # Main program
│── requirements.txt      # Dependencies
│── README.md             # Documentation

## 🛠️ Requirements
- Python 3.9
- OpenCV
- face_recognition
- numpy
- pandas
- pyttsx3
- openpyxl

Install dependencies with:

```bash
pip install -r requirements.txt
```
👤 Author

Created by Abhay Singh Gurjar
