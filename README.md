# Gesture Controlled Virtual Mouse &nbsp;[![](https://img.shields.io/badge/python-3.12.0-blue.svg)](https://www.python.org/downloads/) [![platform](https://img.shields.io/badge/platform-windows-green.svg)](https://github.com/Rohit20Raj/desktop-assistant) 

Gesture Controlled Virtual Mouse makes human computer interaction simple by making use of Hand Gestures and Voice Commands. The computer requires almost no direct contact. All i/o operations can be virtually controlled by using static and dynamic hand gestures along with a voice assistant. This project makes use of the state-of-art Machine Learning and Computer Vision algorithms to recognize hand gestures and voice commands, which works smoothly without any additional hardware requirements. It leverages models such as CNN implemented by [MediaPipe](https://github.com/google/mediapipe) running on top of pybind11. It consists of two modules: One which works direct on hands by making use of MediaPipe Hand detection, and other which makes use of Gloves of any uniform color. Currently it works on Windows platform.


# Getting Started

### Pre-requisites
Python: (>3.8) <br/>
Any code editor

### Procedure

Step 1: Clone the git repository<br/>
```bash
git clone https://github.com/xenon-19/Gesture-Controlled-Virtual-Mouse.git
```
Step 2: Navigate to the cloned repository
```bash
cd Gesture-Controlled-Virtual-Mouse
```
Step 3: Create a virtual environment
```bash
python -m venv gest
```
Step 4: Activate the virtual environment
On Windows
```bash
.\gest\Scripts\activate
```
On Mac/Unix
```bash
source gest/bin/activate
```
Step 5: Install required packages
```bash
pip install -r requirements.txt
```
Step 6: Install PyAudio and pywin32
```bash
pip install PyAudio pywin32
```
Step 8: Navigate to src folder in repository
```bash
cd src
```
Step 9: To run the voice assistant
```bash
python Proton.py
```
Step 10: To run virtual mouse
```bash
python Gesture_Controller.py
```
Step 11: Deactivate the virtual environment
```bash
deactivate
```
