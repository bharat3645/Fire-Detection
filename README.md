# 🔥 Fire Detection from Satellite Images

![Streamlit](https://img.shields.io/badge/Built%20With-Streamlit-red?logo=streamlit)
![TensorFlow](https://img.shields.io/badge/Model-TensorFlow-blue?logo=tensorflow)
![Status](https://img.shields.io/badge/Status-Production-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)

> A lightweight and interactive web application powered by a deep learning model to detect **fire** in satellite images in real-time. Designed for wildfire detection, remote sensing, and early warning systems.

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
git clone https://github.com/bharat3645/Fire-Detection.git
cd Fire-Detection
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the app

```bash
streamlit run app.py
```

Streamlit will open the app in your browser. Upload a satellite image (`.jpg`, `.jpeg`, or `.png`) and click **Detect Fire** to get a prediction with a confidence score.

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
