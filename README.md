# 🧠 American Sign Language Detection and Translator System

This project, **Sign Language to Speech Conversion using Machine Learning**, enables the recognition of American Sign Language (ASL) gestures and converts them into **spoken words or sentences**. It is designed to bridge the communication gap for individuals who use sign language.

---

## 🎯 Features

- 🔴 **Real-Time Recognition**: Converts live webcam feed into recognized gestures.
- ✅ **Robust Prediction**: Implements stabilization for accurate gesture recognition.
- 🧩 **Word and Sentence Formation**: Supports gesture segmentation for space and full stop.
- 🔊 **Text-to-Speech Conversion**: Speaks out the recognized text using `pyttsx3`.
- 🖥️ **User-Friendly GUI**: Displays current alphabet, word, and sentence in real time.

---

## 🌟 Project Highlights

- 📸 **Custom Dataset Creation**: Built from scratch by capturing our own ASL gestures dataset.
- ✋ **ASL Gesture Coverage**: Includes A-Z alphabets, 0–9 digits, a gesture for space, and one for full stop.

---

## 🧠 ASL Characters

Recognizes:
- 26 letters of the English alphabet (A–Z)
- 10 numerical digits (0–9)

---

## 🔧 Tech Stack

- **Languages**: Python
- **Libraries**:
  - `MediaPipe`
  - `OpenCV`
  - `Tkinter`
  - `Pyttsx3`
  - `Scikit-learn`
- **Machine Learning Model**: `RandomForestClassifier`

---

### 📥 Clone this repository

```bash
git clone https://github.com/your-username/sign-language-to-speech.git
cd American-Sign-language-Detection-System
```
### Install the Dependencies

pip install -r requirements.txt


### Run the application

python main.py


### 📌 Notes
This project was developed and tested on Python 3.10.16 in a virtual environment.

Ensure that your system satisfies all library version requirements (see requirements.txt).

### 🤝 Contributing
Pull requests are welcome! If you have suggestions, improvements, or new features to propose, feel free to open an issue or PR.




