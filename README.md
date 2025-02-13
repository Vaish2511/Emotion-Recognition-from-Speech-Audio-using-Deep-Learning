# Residential-Load-Forecasting-using-DNN

## Description:
Developed an advanced emotion recognition system using speech audio data. Employed Librosa for audio preprocessing and feature extraction (MFCCs, spectrograms), and built a deep learning model with TensorFlow for classifying emotions. Achieved 90% accuracy on the validation dataset. Deployed a real-time web application for emotion prediction.

## Key Features:
1. Emotion Recognition: Utilize speech audio data and machine learning models to classify emotions in audio recordings, identifying emotional categories such as happiness, sadness, anger, surprise, and neutral.
2. Real-Time Emotion Prediction: Develop a user-friendly web application that predicts emotions in real time from uploaded audio files, providing instant emotion classification using a deep learning model trained with features like MFCCs and spectrograms.

## Dataset:
1. Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) dataset: 1440 speech files and 1012 Song files from RAVDESS. This dataset includes recordings of 24 professional actors (12 female, 12 male), vocalizing two lexically-matched statements in a neutral North American accent. Speech includes calm, happy, sad, angry, fearful, surprise, and disgust expressions, and song contains calm, happy, sad, angry, and fearful emotions. Each file was rated 10 times on emotional validity, intensity, and genuineness. Ratings were provided by 247 individuals who were characteristic of untrained adult research participants from North America. A further set of 72 participants provided test-retest data. High levels of emotional validity, interrater reliability, and test-retest intrarater reliability were reported.

The classes the model wants to predict are the following: (0 = neutral, 1 = calm, 2 = happy, 3 = sad, 4 = angry, 5 = fearful, 6 = disgust, 7 = surprised).

## Techonologies Used:
1. Machine Learning Libraries (E.g., TensorFlow, Scikit - learn)
2. Data Processing Libraries (E.g., Pandas, Numpy)
3. Audio Processing Libraries (E.g., Librosa)

## Target Audience:
1. Developers and researchers in AI, speech processing, and affective computing
2. Organizations in customer service, healthcare, and mental health
3. Individuals interested in real-time emotion recognition for applications

## Why it Matters:
This system enables automated emotion detection, enhancing user interaction in areas like customer service, virtual assistants, and mental health support. By accurately identifying emotions from speech, it helps create more responsive, empathetic systems that can improve communication and decision-making.
