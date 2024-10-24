# Capuchinbird-sound-analysis 🐦

## 🎯 Project Overview
CapuchinNet is an audio-based machine learning project focused on detecting Capuchinbird calls amidst diverse environmental noise. Utilizing spectrogram analysis, YAMNet embeddings, and transfer learning, this project builds an effective classification model to distinguish Capuchinbird calls from other noises.

## 🚀 Features
- #### 🎵 Preprocessing Methods:

  - White Noise Addition
  - Volume Normalization
  - High/Low-Frequency Filtering
- #### 📊 Audio Transformation:

  - Waveform to Spectrogram Conversion
  - STFT Spectrogram Analysis
  - Visualization of Spectrograms and Predictions
- #### 🧠 Machine Learning Models:

  - CNN Model: Trained from scratch to classify audio spectrograms.
  - YAMNet-based Transfer Learning: Leverages Google’s YAMNet embeddings for efficient audio classification.
- #### 📈 Model Evaluation:

  - Performance visualization with loss & accuracy plots.
  - Confusion Matrix Analysis.
## 📂 Directory Structure
```
capuchinbird-sound-analysis/
│
├── Parsed_Capuchinbird_Clips/      # Contains Capuchinbird audio samples  
├── Parsed_Not_Capuchinbird_Clips/  # Contains non-Capuchinbird samples  
├── Forest Recordings/              # Audio clips for testing  
├── Capuchinbird-sound-analysis.py  # Main training script  
├── submission.csv                  # Results with detected bird call counts  
└── README.md                       # Project documentation
```
## 📊 Results
- Test Accuracy: X%
- Number of Correctly Detected Calls: Y / Z
## 🛠️ Technologies Used
- Python
- TensorFlow & Keras
- YAMNet
- pydub
- Seaborn & Matplotlib
