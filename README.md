# Emotion-Detection

This project implements emotion detection on facial images using Convolutional Neural Networks (CNNs). It uses the FER-2013 dataset to classify images into seven emotion categories, addressing class imbalance, model optimization, and achieving robust performance through advanced architectures like ResNet50v2 and VGG16.

## Project Overview

Emotion detection is a powerful application of deep learning that can be used in various fields, including human-computer interaction, mental health analysis, and sentiment analysis. This project classifies emotions into seven categories (e.g., anger, happiness, sadness) using a CNN-based approach.

## Key Features

- **Class Imbalance Handling**: To improve the model's robustness, class imbalance in the FER-2013 dataset was addressed through image augmentation techniques and custom class weights.
- **Custom CNN Architectures**: Designed and experimented with various CNN models, including advanced architectures like VGG16 and ResNet50v2, to optimize model performance for emotion classification.
- **Performance Metrics**: The final model, based on ResNet50v2, achieved a **66% accuracy**. Detailed performance is presented using precision, recall, and F1 scores for each of the seven emotion labels, providing a comprehensive view of model efficacy.

## Dataset

The project utilizes the **FER-2013** dataset, a large dataset of labeled facial expressions that includes the following emotion labels:

- Angry
- Disgust
- Fear
- Happy
- Sad
- Surprise
- Neutral

## Tech Stack

- **Languages**: Python
- **Deep Learning Frameworks**: TensorFlow, Keras
- **CNN Architectures**: ResNet50v2, VGG16

## Model Training

1. **Data Preprocessing**: Images were resized, normalized, and augmented to ensure balanced training data.
2. **Architecture Selection**: Several CNN architectures were designed and tested, including custom models and pretrained architectures like VGG16 and ResNet50v2.
3. **Model Evaluation**: The final model achieved an overall accuracy of **66%**, with precision, recall, and F1 scores calculated across each emotion class.

## Results

The best-performing model based on ResNet50v2 yielded the following metrics:

- **Overall Accuracy**: 66%
- **Detailed Metrics**: Precision, recall, and F1 scores were calculated for each of the seven emotions, revealing strengths in certain classes while identifying areas for potential improvement.

