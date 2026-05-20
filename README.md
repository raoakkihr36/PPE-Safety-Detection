# PPE-Safety-Detection
AI based real time PPE detection system 
# 🦺 PPE Safety Detection System

An AI-based real-time Personal Protective Equipment (PPE) 
detection system built using YOLOv8 and OpenCV.
Automatically detects missing safety gear and triggers 
alerts to prevent workplace accidents.

##  Features

- 🔴 Real-time helmet (hardhat) detection via live camera
- 🔊 Instant beep alarm when helmet not detected
- 📸 Auto screenshot saved every 5 seconds on violation
- 👷 Person detection with bounding box
- ⚡ Fast and lightweight — runs on standard webcam

## Tech Stack

- Python
- YOLOv8 (Ultralytics)
- OpenCV
- Roboflow Dataset
- winsound (alert system)
- 
##  Project Structure

PPE-Safety-Detection/
│
├── best.pt           # Trained YOLO model
├── main.py           # Main detection script
├── captures/         # Auto-saved violation screenshots
└── README.md

## How to Run

1. Clone the repository
git clone https://github.com/yourusername/PPE-Safety-Detection.git

2. Install dependencies
pip install ultralytics opencv-python

3. Run the project
python main.py

4. Press 'Q' to quit

## 📸 Sample Output

![Detection Screenshot](images/sample.jpg)

## Real World Application

This system can be deployed at:
- Construction sites
- Manufacturing plants
- Industrial warehouses
- Mining facilities

## Author
ALOK  — BTech AI & DS
