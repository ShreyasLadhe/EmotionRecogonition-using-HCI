
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

### Repository Structure

- `face/`: Contains the CNN model and associated scripts for facial emotion recognition.
- `voice/`: Includes the LSTM model and scripts for processing and analyzing audio data.
- `emotions.py`: Main script for processing and integrating the face and voice emotion recognition models.

### Running the Models

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/emotion-recognition-hci.git
    cd emotion-recognition-hci
    ```

2. **Facial Emotion Recognition**:

    Run the following command to start the facial emotion recognition model:

    ```bash
    python face/emotion_recognition_face.py
    ```

3. **Voice Emotion Recognition**:

    Use the following command to start the voice emotion recognition model:

    ```bash
    python voice/emotion_recognition_voice.py
    ```

## How to Use

- **Facial Recognition**: Load an image or video feed, and the CNN model will classify the detected face into an emotion.
- **Voice Recognition**: Provide an audio file or live voice input, and the LSTM model will predict the emotional tone.

## Project Files

- `emotions.py`: Main script combining the outputs of both face and voice models.
- `face/`: Folder with files for facial emotion detection.
- `voice/`: Folder containing the voice emotion detection code and LSTM model.

## Results

This project outputs the recognized emotion from each input source (face and voice), providing a dual-modal understanding of the user's emotional state. Outputs can be visualized in real-time or saved for post-analysis.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
