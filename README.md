
# Emotion Recognition using HCI

This project provides an emotion recognition system utilizing Human-Computer Interaction (HCI) methodologies, focusing on voice and facial expressions. This repository includes models for facial and vocal emotion recognition, built using Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks.

## Project Overview

This project aims to detect human emotions through two primary HCI channels:
1. **Facial Emotion Recognition**: A CNN model identifies emotions from facial expressions.
2. **Voice Emotion Recognition**: An LSTM-based model analyzes vocal features to detect emotions.

Both models work in tandem, providing a comprehensive understanding of emotions by combining visual and auditory data.

## Features

- **Face Emotion Recognition**:
  - Utilizes CNN for feature extraction from images.
  - Detects emotions based on facial expressions in real-time.

- **Voice Emotion Recognition**:
  - Employs LSTM for processing time-series audio features.
  - Analyzes vocal tones to infer emotional states.

## Installation

### Prerequisites

Ensure you have the following libraries installed:

```bash
pip install numpy pandas matplotlib tensorflow keras opencv-python librosa
```
## Results

This project outputs the recognized emotion from each input source (face and voice), providing a dual-modal understanding of the user's emotional state. Outputs can be visualized in real-time or saved for post-analysis.

