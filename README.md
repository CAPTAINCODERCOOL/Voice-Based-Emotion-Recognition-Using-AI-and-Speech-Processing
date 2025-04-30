# 🎙️ Voice-Based Emotion Recognition Using AI

This project focuses on recognizing human emotions from speech using deep learning techniques and signal processing. It combines MFCC-based feature extraction with a powerful neural network model to classify emotions like *happy*, *sad*, *angry*, and *neutral* from voice recordings.


---

## 🚀 Features

- 🎧 Detects emotion from voice recordings
- 🔍 MFCC feature extraction for audio signal processing
- 🧠 Deep neural network for multi-class emotion classification
- 🗂 Real-time audio classification & dataset preprocessing
- 📊 Accuracy visualization using confusion matrices

---

## 🛠 Tech Stack

- Python 3
- TensorFlow / Keras
- NumPy, Pandas
- librosa
- scikit-learn
- Matplotlib, Seaborn

---

## 📦 Installation

1. Clone this repository:
```bash
git clone https://github.com/CAPTAINCODERCOOL/emotion-recognition-from-speech.git
cd emotion-recognition-from-speech
Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
(Optional) Use your own audio dataset, or rely on the pre-organized folders.

🎯 How It Works
Loads WAV audio files from datasets

Extracts MFCCs (Mel-frequency cepstral coefficients)

Trains a neural network to classify emotions into:

Happy 😊

Angry 😠

Sad 😢

Fear 😨

Neutral 😐

📂 Project Structure
bash
Copy
Edit
emotion-recognition/
├── audio/                      # Sample audio files for testing
├── datasets/                   # Training datasets (e.g., RAVDESS, SAVEE)
├── extract_features.py         # MFCC + label extraction
├── model.py                    # Training and prediction model
├── predict.py                  # Predict emotion from new audio
├── requirements.txt
└── README.md
🔬 Example Usage
bash
Copy
Edit
python model.py
python predict.py --input audio/sample.wav
📊 Evaluation
Confusion Matrix

Accuracy & loss plots

Precision, recall, F1-score

Test on unseen audio files

Future Enhancements
Add real-time microphone input

Expand to multilingual datasets

Convert into a Streamlit Web App

Deploy via Flask for real-world applications

Dataset Link https://drive.google.com/drive/folders/1fTN2VkAcTycXCCXmQ71k5ioQmxTMoLm7?usp=sharing


📜 License
This repository follows the original MIT License.

🌐 Connect With Me
GitHub: CAPTAINCODERCOOL

LinkedIn: chiragpatil04

Email: chiragpatilprofessional@gmail.com
