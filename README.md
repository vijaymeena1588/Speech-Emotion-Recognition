# 🎤 Speech Emotion Recognition (RAVDESS Dataset)

This repository contains a **Speech Emotion Recognition (SER)** system built using the **RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)** dataset. The goal of this project is to classify human emotions from speech using **machine learning and deep learning techniques**.

---

## 🚀 Features
- Uses the **RAVDESS dataset** (24 professional actors, 8 emotions).
- Audio preprocessing with **Librosa**.
- Extracts features: **MFCCs, Chroma, Mel Spectrogram, Spectral Contrast, Tonnetz**.
- Machine learning models: **Random Forest, SVM, Gradient Boosting**.
- Deep learning models: **CNN / LSTM** for advanced classification.
- Achieves high accuracy in multi-class emotion detection.

---

## 📂 Project Structure
```bash
Speech_Emotion_Recognize/
│── data/                 # RAVDESS dataset (not included, download separately)
│── notebooks/            # Jupyter notebooks for experiments
│── models/               # Saved ML/DL models
│── src/                  # Source code
│   ├── preprocess.py     # Audio preprocessing and feature extraction
│   ├── train_ml.py       # Train ML models
│   ├── train_dl.py       # Train deep learning models
│   ├── evaluate.py       # Evaluation metrics
│── requirements.txt      # Python dependencies
│── README.md             # Project documentation
---

## 📊 Dataset
- **RAVDESS Dataset** – [Download here](https://zenodo.org/record/1188976)
- Contains **24 professional actors** speaking with **8 emotions**:
  - Neutral, Calm, Happy, Sad, Angry, Fearful, Disgust, Surprised.

---

## ⚙️ Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/Speech_Emotion_Recognize.git
cd Speech_Emotion_Recognize

# Create virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
