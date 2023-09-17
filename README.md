# Gesture2Text

# Sign Language to Text Conversion System

## Introduction

Sign language plays a vital role in facilitating communication for individuals with hearing impairments. However, the communication barrier between those who can speak and hear and those who use sign language can be challenging to overcome. In India alone, around 7.5-8 million people suffer from speech and hearing disabilities, and this number increases significantly on a global scale [1]. To enhance communication accessibility, we have developed a system that translates sign language gestures into text.

## Problem Statement

The primary goal of this project is to create an application that can detect predefined sign language symbols in real-time through hand gestures. Additionally, the application provides users with the capability to store these sign language translations and customize their own gestures. This solution aims to address the challenges faced by individuals who cannot communicate verbally by providing technological assistance to bridge the gap in expression.

## Overview of Project

Our project revolves around developing a model that can recognize and interpret sign language motions into written text using Convolutional Neural Networks (CNNs). The project consists of the following key steps:

1. **Data Collection:** We assemble a comprehensive database of written text and sign language gestures, which will be used to train the CNN model.

2. **Data Pre-processing:** We prepare the dataset for use with the CNN model, which may involve resizing images, normalizing pixel values, and splitting the dataset into training and testing sets.

3. **Model Training:** We create and train the CNN model using the dataset. Techniques such as transfer learning may be employed to enhance model performance.

4. **Real-time Deployment:** We deploy the trained model in a real-world application that can translate sign language gestures into written text in real-time.

## Project Details

This project specifically focuses on the recognition of the 26 English alphabets in sign language, aiming to improve the accuracy and context of the converted text. It comprises the following major components:

- **Pre-processing and Segmentation:** The input hand gesture undergoes pre-processing and segmentation to prepare it for analysis.

- **Feature Extraction:** Relevant features are extracted from the segmented hand gesture.

- **Sign Identification:** A classifier predicts the hand gesture, determining which letter corresponds to the most similar motion.

- **Sign to Text Conversion:** The recognized gesture is converted into text and displayed as output on the graphical user interface (GUI).

In summary, our system processes the hand gesture through filtering and classification to identify the corresponding English alphabet, enhancing communication for individuals who use sign language.

## References

[1] [Insert Reference Link Here]
[2] [Insert Reference Link Here]

For more details, please refer to the documentation and source code in this repository.

