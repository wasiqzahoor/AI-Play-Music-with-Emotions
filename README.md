# AI Gesture Assistant

![Python 3.x](https://img.shields.io/badge/Python-3.8+-blue.svg) ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg) ![MediaPipe](https://img.shields.io/badge/MediaPipe-Latest-red.svg) ![OpenCV](https://img.shields.io/badge/OpenCV-Latest-blueviolet.svg)

An interactive AI assistant that recognizes gestures and facial expressions to perform tasks like playing music. This project uses MediaPipe for real-time landmark detection and TensorFlow/Keras for model training and inference.

---

## 🌟 Features

* **Custom Gesture Recognition:** Collect data for your own unique gestures or emotions, and train the model to recognize them.
* **Real-time Inference:** The application uses your webcam to detect gestures and expressions in real-time.
* **YouTube Music Integration:** When the assistant recognizes a specific gesture (e.g., a "play" gesture), it automatically opens a Youtube for music.
* **User-Friendly Interface:** A simple menu-driven UI (using Tkinter) lets you easily switch between data collection, training, and inference modes.
* **Modular Workflow:** The entire process is integrated into a single script, making it easy to manage and run.

---

## 🛠️ Prerequisites

Before running the project, you need to install the following libraries. It is highly recommended to use a virtual environment.

```bash
pip install opencv-python mediapipe numpy tensorflow keras
