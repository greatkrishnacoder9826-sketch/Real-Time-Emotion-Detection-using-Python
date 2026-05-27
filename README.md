Real-Time Emotion Detection using Python

A Python-based real-time emotion detection project that uses a webcam to detect human faces and analyze emotions using DeepFace and OpenCV.

Features
Real-time webcam emotion detection
Face detection using Haar Cascade Classifier
Emotion analysis using DeepFace
Displays detected emotion on live video feed
Simple and beginner-friendly project
Technologies Used
Python
OpenCV (cv2)
DeepFace
TensorFlow / Keras
Project Structure
├── emotion_detection.ipynb
├── haarcascade_frontalface_default.xml
└── README.md
Installation
1. Clone the Repository
git clone https://github.com/your-username/emotion-detection.git
cd emotion-detection
2. Install Required Libraries
pip install opencv-python
pip install deepface
pip install tf_keras
Required File

Download the Haar Cascade XML file:

haarcascade_frontalface_default.xml

You can get it from the OpenCV GitHub repository.

How to Run

Run the Jupyter Notebook:

jupyter notebook

Open the notebook and run all cells.

Working
Captures video from webcam
Detects faces in each frame
Extracts face region
Uses DeepFace to analyze emotions
Displays dominant emotion on screen
Example Emotions Detected
Happy
Sad
Angry
Neutral
Surprise
Fear
Future Improvements
Add age and gender detection
Save emotion logs
Improve detection accuracy
Create GUI application
Author

Krishna Great

License

This project is open-source and available under the MIT License.
