Hand Gesture Recognition - Victory Sign
📌 Project Description
This project uses Python, OpenCV, and MediaPipe to detect hand gestures through a webcam.
The program recognizes the Victory Sign (V) gesture by checking finger positions. When the gesture is detected, it displays VICTORY on the screen and saves a screenshot.
🚀 Features
Real-time webcam video processing
Hand landmark detection using MediaPipe
Recognition of the Victory Sign gesture
Display gesture status on the webcam
Save a screenshot when the Victory Sign is detected
Press q to exit the program
🛠️ Technologies Used
Python
OpenCV
MediaPipe
📦 Installation
Install the required libraries:
pip install opencv-python mediapipe 
▶️ How to Run
Clone the repository:
git clone YOUR_REPOSITORY_URL 
Open the project folder:
cd YOUR_PROJECT_FOLDER 
Run the Python file:
python main.py 
Make sure your webcam is connected and available.
🖐️ How It Works
The program opens the webcam.
MediaPipe detects hand landmarks.
The program checks the positions of the fingers.
If two fingers are open and the other fingers are closed, it recognizes the Victory Sign.
The program displays VICTORY or NOT VICTORY.
When the Victory Sign is detected, a screenshot is saved as screen.png.
📁 Project Structure
Hand-Gesture-Recognition/ │ ├── main.py ├── screen.png └── README.md 
🎯 Purpose
This project is a beginner-friendly computer vision project for learning hand tracking, gesture recognition, and webcam processing with Python.
👨‍💻 Author
Created as a Python programming project.
