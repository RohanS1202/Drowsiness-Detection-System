# Drowsiness Detection System

## Overview
The **Drowsiness Detection System** is a real-time application that detects driver drowsiness using computer vision techniques. It employs facial recognition and eye-tracking to determine signs of fatigue and triggers an alarm to alert the user.

## Features
- Real-time detection of drowsiness using OpenCV and deep learning models.
- Uses Haar cascade classifiers for face and eye detection.
- Triggers an alarm sound when drowsiness is detected.
- Can be integrated into vehicles for driver safety.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- OpenCV (`cv2`)
- NumPy
- TensorFlow/Keras (if using a deep learning model)
- Pygame (for playing alarm sounds)

### Steps to Install
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/Drowsiness-Detection-System.git
   cd Drowsiness-Detection-System
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Run the main script:
   ```sh
   python drowsiness_detection.py
   ```
2. The system will access your webcam and analyze facial features.
3. If drowsiness is detected, an alarm will sound.

## Project Structure
```
Drowsiness-Detection-System/
│── drowsiness_detection.py   # Main script for detection
│── model.py                  # Model handling script
│── haar cascade files/       # Pre-trained Haar cascade models
│── alarm.wav                 # Sound file for alert
│── README.md                 # Project documentation
│── requirements.txt          # Dependencies list
```

## Contributing
Feel free to contribute to this project. Fork the repository, make changes, and submit a pull request.


