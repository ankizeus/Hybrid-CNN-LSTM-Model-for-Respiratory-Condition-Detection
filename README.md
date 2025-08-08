
# 🫁 Lung Disease Detection Using Audio Classification

This is a web-based application that detects various lung diseases from audio recordings of respiratory sounds using deep learning and audio signal processing.

## 🔍 Features

- 🎤 Upload respiratory audio files (e.g., breath or lung sounds)
- 🎼 Convert audio to **spectrograms** using `librosa`
- 🧠 Predict diseases using a **Convolutional Neural Network (CNN)**
- 💡 Detects conditions like:
  - Asthma
  - COPD
  - Pneumonia
  - Lung Fibrosis
  - Pleural Effusion
  - Heart Failure-related conditions
- 🌐 Built with **Flask** and rendered with interactive HTML/CSS/JS
- 📊 Displays **diagnosis result** along with the spectrogram visualization

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python, Flask
- **Deep Learning:** TensorFlow/Keras
- **Audio Processing:** Librosa, Matplotlib
- **Visualization:** Spectrogram generation and display

## 🚀 How It Works

1. User uploads an audio file through the web interface.
2. The system extracts a spectrogram from the audio input.
3. The spectrogram is passed to a CNN model trained to classify lung diseases.
4. The prediction result and spectrogram image are displayed.

## 🗂️ Project Structure

```
lung-disease-detection/
├── app.py
├── templates/
│   ├── index.html
│   └── result.html
├── static/
│   └── [spectrogram images]
├── uploads/
│   └── [uploaded audio files]
├── requirements.txt
└── README.md
```

## ▶️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/lung-disease-detection.git
cd lung-disease-detection
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Flask app
```bash
python app.py
```

### 4. Open in browser
Visit `http://127.0.0.1:5000/` in your browser to use the application.

## 📄 License

This project is for educational and research purposes only.
