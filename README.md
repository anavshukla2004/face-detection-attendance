## 🎯 Face Recognition Attendance System

A smart Face Recognition–Based Attendance System that automatically marks attendance using a webcam.
The system uses computer vision and deep learning techniques to recognize faces in real time and store attendance records efficiently.

## 📌 Project Overview

Traditional attendance systems are time-consuming and prone to proxy attendance.
This project solves that problem by using AI-powered face recognition to:

Identify registered individuals

Mark attendance automatically

Store attendance records with date and time

Reduce manual effort and errors

## 🚀 Features

🔍 Real-time Face Detection & Recognition

🧠 Deep Learning–based face encoding

📸 Webcam-based live recognition

🕒 Automatic Date & Time logging

📁 CSV-based Attendance Storage

🚫 Prevents Duplicate Attendance

⚡ Fast and Accurate Recognition

## 🛠️ Technologies Used
Category	Technology
Programming Language	Python
Computer Vision	OpenCV
Face Recognition	face_recognition (Dlib)
Data Handling	CSV, Pandas
IDE	VS Code
Camera	System Webcam
📂 Project Structure
Attendance-System/
│
├── Images/                 # Training images (known faces)
├── attendance.csv          # Attendance records
├── main.py                 # Main execution file
├── requirements.txt        # Required libraries
└── README.md               # Project documentation

## ⚙️ How It Works

Load Known Faces

Images stored in the Images/ folder are used for training.

Face Encoding

Facial features are converted into numerical encodings.

Live Camera Feed

Webcam captures real-time video frames.

Face Matching

Live faces are compared with stored encodings.

Attendance Marking

Name, date, and time are saved in a CSV file.

▶️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/attendance-system.git
cd attendance-system

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Add Training Images

Add clear face images inside the Images/ folder

Image name should be the person’s name

Example:

Anav.jpg
Rahul.png

4️⃣ Run the Program
python main.py
