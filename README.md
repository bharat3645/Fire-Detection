# 🔥 Fire Detection from Satellite Images

![Streamlit](https://img.shields.io/badge/Built%20With-Streamlit-red?logo=streamlit)
![TensorFlow](https://img.shields.io/badge/Model-TensorFlow-blue?logo=tensorflow)
![Status](https://img.shields.io/badge/Status-Production-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)

> A lightweight and interactive web application powered by a deep learning model to detect **fire** in satellite images in real-time. Designed for wildfire detection, remote sensing, and early warning systems.

---

## 📸 Demo Preview

Upload any satellite image (JPG, PNG) and get instant fire detection results with confidence.

<p align="center">
  <img src="https://media.giphy.com/media/U5xkM8E4cP5lu/giphy.gif" width="60%" alt="Fire Detection Demo">
</p>

---

## 🧠 About the Model

- **Format:** Keras `.h5`
- **Input Shape:** `64x64x3` (RGB image)
- **Output:** `["No Fire", "Fire 🔥"]`
- **Model Type:** CNN
- **Prediction:** Softmax (2 classes) with confidence display

---

## 🛠️ Installation

### ✅ Prerequisites

- Python 3.8+
- pip

### 📦 Setup

1. Clone the repository

```bash
git clone https://github.com/bharat3645/fire-detection-streamlit.git
cd fire-detection-streamlit
