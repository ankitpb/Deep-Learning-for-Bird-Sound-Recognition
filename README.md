# Bird Sound Recognition using Deep Learning

This project focuses on classifying bird species from audio recordings using spectrogram-based deep learning models. It includes both binary and multiclass classification tasks using custom convolutional neural networks (CNNs).

## Project Overview

- **Binary Classification**: Distinguish between two most common species (House Sparrow vs. Song Sparrow).
- **Multiclass Classification**: Predict one of 12 bird species commonly found in the Seattle area.
- **Dataset**: Subset of the Birdcall Competition data (originally from Xeno-Canto).
- **Input Format**: Mel-spectrograms of shape `128 × 517` generated from `.mp3` audio clips.

## 🧠 Models Used

- Custom CNNs with:
  - Batch normalization
  - Adaptive average pooling
  - Dropout regularization
- Focal Loss to address class imbalance
- On-the-fly spectrogram augmentation (frequency and time masking)

## 📈 Key Results

| Task                        | Accuracy |
|-----------------------------|----------|
| Binary Classification       | 80.7%    |             
| Multiclass Classification   | 35.2%    |           
