# 🗣️ LipSpeak

**LipSpeak** is an innovative lip-reading system developed during the **DevSoc'25 Hackathon**. This project uses machine learning and computer vision to accurately predict spoken words based solely on lip movements — without any audio input. It showcases how AI can enable silent and privacy-conscious communication in real-world scenarios.

## 🚀 Overview

The primary goal of LipSpeak is to analyze video inputs, detect lip movements, and convert them into predicted words using a trained machine learning model. By eliminating the need for audio, LipSpeak can be useful in environments with noise, for accessibility solutions, or where silent communication is essential.

## 🧠 Technologies Used

- **Python**
- **OpenCV** – for face and lip region detection
- **TensorFlow / Keras** – for deep learning model development
- **NumPy & Pandas** – for data preprocessing
- **Matplotlib / Seaborn** – for data visualization (optional)

## 📦 Features

- Lip detection and tracking from video frames
- Preprocessing pipeline for mouth-region extraction
- Deep learning model to classify words based on lip movement
- Silent speech recognition without any audio dependency

## 🎯 Use Cases

- Assistive tech for the hearing or speech impaired
- Silent command systems for security or industrial use
- Enhancing human-computer interaction in noisy environments

## 🛠️ How It Works

1. **Video Input** – Users upload or stream a video of a person speaking.
2. **Lip Region Detection** – OpenCV is used to detect and isolate the mouth area in each frame.
3. **Frame Preprocessing** – Frames are resized, normalized, and prepared as input for the model.
4. **Word Prediction** – A CNN/RNN-based model processes the visual input and outputs the predicted word.


## 👥 Team

This project was built as part of **DevSoc'25 Hackathon** by a passionate team of developers and AI enthusiasts.


## 📝 License

This project is for educational and demonstration purposes. Feel free to fork or build upon it.

---


