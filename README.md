# Voice-Gender-Classification
This project implements a machine learning and deep learning pipeline for gender detection based on voice samples from the [Voice Gender Detection dataset](https://dagshub.com/kingabzpro/voice_gender_detection). It utilizes acoustic features such as Mel Frequency Cepstral Coefficients (MFCCs) and Mel Spectrograms to classify voices as male or female. The solution compares traditional machine learning models like Gradient Boosting and Random Forest with a custom Convolutional Neural Network (CNN) architecture for enhanced performance.

Features:
- Dataset: Diverse voice samples categorized by gender, ensuring balance and variation across accents, age groups, and vocal intensity.
- Preprocessing: Resampling, noise reduction, MFCC extraction, and Mel Spectrogram generation.
- Models: Compared Gradient Boosting and other ML classifiers with a CNN architecture tailored for audio analysis.
- Evaluation: Achieved 89.76% accuracy using Gradient Boosting and optimized CNN performance to reduce overfitting.
- Future Work: Explore data augmentation, enhanced CNN architectures, and improved dataset diversity.
