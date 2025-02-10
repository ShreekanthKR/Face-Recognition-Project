# Face Recognition Attendance System

## Overview
This project is a Face Recognition Attendance System that uses OpenCV, NumPy, and the Face Recognition library to capture real-time images from a webcam, recognize faces, and log attendance in a CSV file.

## Features
- Detects and recognizes faces in real-time.
- Compares faces with stored training images.
- Logs attendance with a timestamp in `Attendance.csv`.
- Uses OpenCV for image processing.

## Installation & Setup
### Prerequisites
Ensure you have Python installed. Then, install the required dependencies:

pip install opencv-python numpy face_recognition


### Run the Script
python attendance_system.py


## Folder Structure
```
📂 Face-Recognition-Attendance  
 ┣ 📂 Training_images      # Store known faces  
 ┣ 📜 attendance_system.py # Main Python script  
 ┣ 📜 Attendance.csv       # Stores attendance logs  
 ┣ 📜 README.md            # Documentation  
 ┗ 📜 requirements.txt     # List of dependencies  
```

## Usage
1. Place images of individuals in the `Training_images` folder.
2. Run the script to start face recognition.
3. The system will detect and log attendance in `Attendance.csv`.



## Technologies Used
- Python
- OpenCV
- NumPy
- Face Recognition Library



