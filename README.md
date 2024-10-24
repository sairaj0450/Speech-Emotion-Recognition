# Real-Time Speech Emotion Recognition (SER)

This project uses a Deep Learning approach to detect emotions from audio in real time using an LSTM (Long Short-Term Memory) model in Keras.

## Overview
The goal is to develop an AI system that analyzes audio inputs in real time, detects emotions, and presents them. The system uses Deep Neural Networks (DNN), specifically LSTM, which is ideal for time-series analysis like speech data.

## Dataset
The model is trained using emotional speech data from two sources:
- **RAVDESS** (Ryerson Audio-Visual Database of Emotional Speech and Song)
- **TESS** (Toronto Emotional Speech Set)

## How It Works
1. **Real-Time Audio Analysis**: The system takes live audio input through a microphone.
2. **Emotion Detection**: The audio is analyzed in short cycles, and the model identifies the emotions present in each segment.
3. **Automatic Stop**: If the system detects 2 seconds of silence, it stops automatically.

## Results
The system achieves an 87% accuracy in recognizing emotions from speech. The noise reduction and QA enhancements ensure reliable analysis, even in challenging scenarios.