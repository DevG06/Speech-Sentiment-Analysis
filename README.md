# Speech Sentiment Analysis

This project aims to analyze and classify emotions from speech signals using various deep learning models. The datasets used in this project include Crema, Ravdess, Savee, and Tess. Data augmentation techniques such as noise introduction, pitch shifting, and stretching were applied to enhance the dataset. Features such as MFCCs, Energy and Entropy of Energy, Zero Crossing Rate, Mel-Spectrogram, and Spectral Features were extracted for analysis.

## Table of Contents

- [Introduction](#introduction)
- [Datasets](#datasets)
- [Data Augmentation](#data-augmentation)
- [Feature Extraction](#feature-extraction)
- [Models](#models)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction

Speech sentiment analysis is the task of classifying emotions in spoken language. It has applications in various fields such as customer service, mental health monitoring, and human-computer interaction. This project leverages multiple datasets and a combination of data augmentation and feature extraction techniques to build and evaluate four machine learning models: ANN, CNN, LSTM, and CNN-LSTM.

## Datasets

The following datasets were used in this project:

- **Crema**: Crowd-sourced Emotional Multimodal Actors dataset.
- **Ravdess**: Ryerson Audio-Visual Database of Emotional Speech and Song.
- **Savee**: Surrey Audio-Visual Expressed Emotion dataset.
- **Tess**: Toronto Emotional Speech Set.

## Data Augmentation

To enhance the dataset and improve model robustness, the following data augmentation techniques were applied:

- **Noise Introduction**: Adding background noise to the audio samples.
- **Pitch Shifting**: Altering the pitch of the audio samples.
- **Stretching**: Changing the speed of the audio samples without altering the pitch.

## Feature Extraction

The following features were extracted from the audio data to capture various aspects of the speech signals:

- **MFCCs (Mel-Frequency Cepstral Coefficients)**: Capture detailed spectral information and are widely used in speech and audio processing.
- **Energy and Entropy of Energy**: Provide information about the intensity and variability of speech, which are important for detecting emotions.
- **Zero Crossing Rate**: Useful for distinguishing between different types of speech sounds.
- **Mel-Spectrogram**: Represents the power spectrum in the mel scale. Captures both temporal and spectral features of the audio signal.
- **Spectral Features (Centroid, Spread, Roll-off)**: Provide a comprehensive description of the spectral characteristics of the speech signal.

## Models

Four machine learning models were built and evaluated for this project:

1. **ANN (Artificial Neural Network)**
2. **CNN (Convolutional Neural Network)**
3. **LSTM (Long Short-Term Memory)**
4. **CNN-LSTM (Convolutional Neural Network - Long Short-Term Memory)**

## Results

The models were evaluated based on their accuracy and other relevant metrics. The CNN model showed the highest performance, achieving a validation accuracy of 70%.

![CNN_Loss curve](https://github.com/user-attachments/assets/9fed9d71-2391-4c29-b882-f4e4e599f5e6)

## Installation

To run this project, you need to have Python installed along with the required libraries. You can install the dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Usage
To use the models for speech sentiment analysis, follow these steps:

1. Clone this repository:
```bash
git clone https://github.com/DevG06/Speech-Sentiment-Analysis.git
```
2. Navigate to project directory:
```bash
cd Speech-Sentiment-Analysis
```

3. Run the Jupyter notebooks provided to preprocess the data, extract features, and train the models.

## License
This project is licensed under the [MIT License](LICENSE).
