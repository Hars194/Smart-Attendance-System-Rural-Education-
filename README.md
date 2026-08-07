# 🎓 Smart Attendance System

An AI-powered Smart Attendance System that combines **RFID Authentication**, **Face Recognition**, and **Raspberry Pi** to provide secure, fast, and automated attendance management. The system prevents proxy attendance by verifying both the RFID card and the student's face before marking attendance.

---

# 📌 Project Overview

Traditional attendance systems are time-consuming and vulnerable to proxy attendance. This project solves these issues by using dual authentication:

1. RFID Card Verification
2. AI Face Recognition

Only when both verifications are successful is attendance stored in the database.

The system is designed for schools, colleges, universities, training institutes, and corporate offices.

---

# ✨ Features

- RFID Card Authentication
- AI Face Recognition
- Dual Authentication
- Real-time Attendance
- Automatic Date & Time Logging
- Student Registration
- Face Dataset Collection
- Attendance Reports
- CSV Export
- Admin Dashboard
- User Login System
- Live Camera Feed
- Duplicate Attendance Prevention
- Offline Data Storage
- Cloud Database Support
- Fast Recognition
- High Accuracy

---

# 🚀 Problem Statement

Manual attendance systems have several issues:

- Proxy attendance
- Time consuming
- Human errors
- Paper waste
- Difficult record management
- Fake attendance
- No real-time monitoring

This project eliminates these problems using Artificial Intelligence.

---

# 💡 Proposed Solution

Each student receives an RFID card.

Attendance Process:

Student
↓

Scan RFID Card
↓

RFID Verification
↓

Camera Captures Face
↓

AI Face Recognition
↓

Face Match?
↓

YES → Attendance Marked

NO → Attendance Rejected

---

# 🛠 Hardware Used

| Component | Description |
|-----------|-------------|
| Raspberry Pi 5 | Main Controller |
| RFID Reader RC522 | Reads RFID Cards |
| RFID Tags | Student Identity |
| Raspberry Pi Camera Module | Face Capture |
| LCD Display (Optional) | Display Messages |
| Buzzer | Success/Error Sound |
| LED Indicators | Status Display |
| Power Supply | 5V 3A Adapter |
| WiFi | Cloud Communication |

---

# 💻 Software Used

- Python
- Flask
- OpenCV
- DeepFace
- FaceNet
- OpenFace
- SQLite
- MySQL
- HTML
- CSS
- JavaScript
- Bootstrap
- Git
- GitHub

---

# 📂 Project Structure

```
Smart-Attendance-System/

│
├── app.py
├── config.py
├── requirements.txt
├── README.md
│
├── database/
│      attendance.db
│
├── models/
│      face_model.py
│      rfid.py
│
├── camera/
│      camera.py
│
├── dataset/
│      student_images/
│
├── templates/
│      index.html
│      login.html
│      register.html
│      dashboard.html
│
├── static/
│      css/
│      js/
│      images/
│
├── attendance/
│      attendance.csv
│
└── exports/
```

---

# ⚙ Working Flow

## Step 1

Student scans RFID card.

↓

## Step 2

RFID Reader sends UID to Raspberry Pi.

↓

## Step 3

Database verifies RFID.

↓

## Step 4

Camera captures student's face.

↓

## Step 5

DeepFace extracts facial embeddings.

↓

## Step 6

AI compares with registered dataset.

↓

## Step 7

If face matches:

✔ Attendance stored

Else

❌ Attendance rejected

---

# 🧠 Face Recognition Process

Camera

↓

Face Detection

↓

Face Alignment

↓

Embedding Generation

↓

Database Comparison

↓

Identity Prediction

↓

Attendance

---

# 🗄 Database Tables

## Students

| Field |
|-------|
| Student_ID |
| Name |
| RFID_UID |
| Department |
| Year |
| Face_Path |

---

## Attendance

| Field |
|-------|
| Attendance_ID |
| Student_ID |
| Date |
| Time |
| Status |
| Device |

---

# 📸 Screenshots

## Home Page

(Add Screenshot)

---

## Registration

(Add Screenshot)

---

## Dashboard

(Add Screenshot)

---

## Live Recognition

(Add Screenshot)

---

## Attendance Report

(Add Screenshot)

---

# 🔄 Attendance Workflow

```
Student
   │
   ▼
Scan RFID
   │
   ▼
RFID Verified
   │
   ▼
Capture Face
   │
   ▼
AI Recognition
   │
   ▼
Match?
 │       │
Yes      No
 │        │
 ▼        ▼
Attendance   Reject
Stored
```

---

# 📊 Advantages

- Contactless Attendance
- Secure Authentication
- No Proxy Attendance
- Real-time Monitoring
- High Accuracy
- Low Cost
- Easy Installation
- Fast Processing
- Cloud Integration
- Easy Report Generation

---

# 📉 Limitations

- Camera quality affects accuracy
- Poor lighting reduces performance
- Internet required for cloud synchronization
- Face mask may reduce accuracy
- Initial registration required

---

# 🔮 Future Enhancements

- QR Code Attendance
- Fingerprint Verification
- GPS Attendance
- Mobile App
- Voice Authentication
- Email Notifications
- SMS Alerts
- Parent Notification
- AI Analytics Dashboard
- Multi-Camera Support
- Cloud Deployment
- AWS Integration
- Firebase Support

---

# 📈 Applications

- Colleges
- Schools
- Universities
- Offices
- Industries
- Hospitals
- Coaching Institutes
- Government Offices
- Libraries
- Research Labs

---

# 📦 Installation

## Clone Repository

```bash
git clone https://github.com/username/Smart-Attendance-System.git
```

---

## Create Virtual Environment

```bash
python -m venv venv
```

---

## Activate Environment

Windows

```bash
venv\Scripts\activate
```

Linux

```bash
source venv/bin/activate
```

---

## Install Requirements

```bash
pip install -r requirements.txt
```

---

## Run Application

```bash
python app.py
```

---

# 📋 Requirements

```
opencv-python
deepface
flask
numpy
pandas
sqlite3
mysql-connector-python
picamera2
tensorflow
Pillow
```

---

# 🔐 Security Features

- Dual Authentication
- Encrypted Database
- RFID Validation
- Face Embeddings
- Duplicate Prevention
- Admin Authentication
- Secure Login

---

# 📊 Performance

| Parameter | Value |
|-----------|--------|
| Recognition Accuracy | 97–99% |
| RFID Detection Time | <1 Second |
| Face Recognition Time | 1–2 Seconds |
| Attendance Time | <3 Seconds |
| Multiple Users | Supported |

---

# 👨‍💻 Author

**Harshal Gajanan Rokade**

B.Tech Information Technology

Nagpur University

### Skills

- Python
- OpenCV
- DeepFace
- Raspberry Pi
- Flask
- Machine Learning
- Computer Vision
- IoT
- SQL
- GitHub

---

# 📜 License

This project is licensed under the MIT License.

---

# ⭐ Support

If you like this project, please give it a ⭐ on GitHub and share it with others.

---

# 📧 Contact

For suggestions or collaborations, feel free to connect through GitHub.
<img width="1492" height="1133" alt="Device Pic" src="https://github.com/user-attachments/assets/9a19c35b-83dd-42ca-8a6e-ab18f0332cc2" />
