# Sign Language Recognition & Translator
**Author:** Afnan Ijaz

---

## Project Overview
A real-time American Sign Language (ASL) recognition app with a desktop GUI. It uses a webcam
to detect hand landmarks, classifies the hand shape into an ASL letter using a trained neural
network, then translates and speaks the result — with support for multiple output languages and
voice input.

**Tech stack:** Python · TensorFlow/Keras · MediaPipe · OpenCV · Tkinter (ttkbootstrap) ·
Google Translate API · Speech Recognition · Text-to-Speech

---

## Features
- Real-time hand tracking via webcam using MediaPipe Hands
- ASL alphabet classification (A–Z, plus space and del) using a trained MLP neural network
- Live translation into English, Urdu, French, Spanish, Chinese, Arabic via Google Translate
- Text-to-speech playback with auto-speak mode
- Voice input mode
- Translation history log, theme toggle, frame capture

---

## How to Run
1. Install Python 3.9–3.11
2. `pip install -r requirements.txt`
3. `python App.py`
4. Allow webcam access, then sign ASL letters to the camera
