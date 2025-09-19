# HACKATHON PROJECT

# Face Recognition Attendance System

A Python-based attendance system that uses **face recognition** to automatically mark attendance, record entry time, and save details into an Excel sheet. The system also provides **voice feedback** when a person’s attendance is marked.

## Features
- Detects and recognizes faces in real-time using a webcam.
- Stores known faces from a demo_photos folder (`demo_photos/`).
- Marks attendance with **Name, Date, Time, and Status** (On Time / Late).
- Prevents duplicate entries for the same day.
- Saves attendance records into `attendance.xlsx` (new sheet created daily).
- Voice announcement using **pyttsx3**.
- Shows total number of people present on the live video feed.

## Requirements
Install dependencies with:

pip install -r requirements.txt

Run the program

python main.py

Requirements

Python 3.8+

OpenCV

face_recognition

numpy

pandas

Future Improvements

Add GUI for easier use

Store attendance in database (MySQL/SQLite)

Export attendance as PDF

Author

Created by Abhay Singh Gurjar


