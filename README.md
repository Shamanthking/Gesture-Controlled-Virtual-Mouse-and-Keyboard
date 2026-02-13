<<<<<<< HEAD
# Gesture-Controlled-Virtual-Mouse-and-Keyboard
=======
# Gesture Controlled Virtual Mouse and Keyboard 🖐️⌨️

## Overview
This project implements a **gesture-controlled virtual mouse and keyboard system** using computer vision techniques.  
It allows users to control mouse movements and keyboard actions through **hand gestures**, eliminating the need for physical input devices.

The system uses a webcam to detect gestures and maps them to mouse and keyboard operations, providing a touchless and interactive user experience.

---

## Project Structure
Gesture-Controlled-Virtual-Mouse-and-Keyboard/
│── src/ # Source code files
│── icons/ # Icons used in the application
│── model.yml # Trained model file
│── haarcascade_frontalface_default.xml# Haar cascade for face detection
│── kc.wav # Audio feedback file
│── mn.png # Image asset
│── CODE_OF_CONDUCT.md # Code of conduct
│── README.md # Project documentation


---

## Technologies Used
- **Programming Language:** Python  
- **Computer Vision:** OpenCV  
- **Machine Learning:** Haar Cascade / Pre-trained models  
- **Input Control:** PyAutoGUI / OS-level input handling  
- **Hardware:** Webcam  

---

## Features
- Hand gesture–based mouse movement  
- Gesture-controlled mouse click actions  
- Virtual keyboard interaction  
- Real-time webcam processing  
- Touch-free human–computer interaction  

---

## How It Works
1. The webcam captures live video frames.  
2. Hand and face detection is performed using OpenCV and Haar cascades.  
3. Recognized gestures are mapped to mouse or keyboard actions.  
4. The system executes the corresponding input operation in real time.  

---

## How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/Gesture-Controlled-Virtual-Mouse-and-Keyboard.git
cd Gesture-Controlled-Virtual-Mouse-and-Keyboard
2️⃣ Install required libraries
pip install opencv-python numpy pyautogui
3️⃣ Run the application
python src/main.py
Ensure your webcam is connected and accessible.

Use Cases
Touchless computer interaction

Accessibility solutions

Human–Computer Interaction (HCI) research

Smart systems and automation

Future Enhancements
Improve gesture accuracy using deep learning

Add more gesture-based shortcuts

Support multi-hand gestures

Optimize performance for low-end systems

Conclusion
This project demonstrates an innovative approach to human–computer interaction by replacing traditional input devices with hand gestures using computer vision.
>>>>>>> df07362fedf40d61a3e1116b6c2c7321d97b1ded
