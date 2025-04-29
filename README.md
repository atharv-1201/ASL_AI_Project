American Sign language Detection and Translator System
Overview
This project, Sign Language to Speech Conversion using Machine Learning, enables the recognition of American Sign Language (ASL) gestures and converts them into spoken words or sentences. It is designed to bridge the communication gap for individuals who use sign language.

🎯 Features
Real-Time Recognition: Converts live webcam feed into recognized gestures.
Robust Prediction: Implements stabilization for accurate gesture recognition.
Word and Sentence Formation: Automatically forms words and sentences with proper segmentation (space and full stop gestures).
Text-to-Speech Conversion: Speaks out the recognized text for better accessibility.
User-Friendly GUI: Displays the current alphabet, word, and sentence in real time.
Project Highlights
Custom Dataset Creation:
We built this project from the ground up by capturing and preparing our custom dataset of ASL gestures, covering A-Z alphabets, 0-9 digits, a gesture for space, and one for full stop.

ASL Characters The 26 letters and 10 digits of American Sign Language (ASL)

🔧 Tech Stack
Languages: Python
Libraries: MediaPipe, OpenCV, Tkinter, Pyttsx3, Scikit-learn
Machine Learning Model: Random Forest Classifier
Usage
Clone this repository:

git clone https://github.com/your-username/sign-language-to-speech.git
cd sign-language-to-speech
Install the required dependencies:

pip install -r requirements.txt
