# Hand Gesture Recognition Using Neural Networks

Welcome to the Hand Gesture Recognition project! This project aims to develop a model that can accurately identify and classify different hand gestures from image or video data, enabling intuitive human-computer interaction and gesture-based control systems.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Results](#results)

## Overview

Hand gesture recognition is a technology that interprets human gestures via mathematical algorithms. This project leverages deep learning techniques to develop a neural network model capable of recognizing and classifying hand gestures from images or video frames. The goal is to create an intuitive interface for human-computer interaction and gesture-based control systems.

## Dataset

We use the [LeapGestRecog](https://www.kaggle.com/gti-upm/leapgestrecog) dataset, which contains hand gesture images captured using the Leap Motion Controller. The dataset includes various gestures performed by different subjects, making it suitable for training and evaluating gesture recognition models.

- **Dataset URL**: [LeapGestRecog](https://www.kaggle.com/gti-upm/leapgestrecog)
- **Categories**: Different hand gestures
- **Data Format**: Images

## Usage

I'd recommend kaggle to work as we are working on a big data set that can be directly imported without uploading in kaggle.

## Model Architecture

The model architecture used for this project is based on Convolutional Neural Networks (CNNs), which are well-suited for image recognition tasks. The model consists of multiple convolutional layers followed by max-pooling layers, fully connected layers, and a softmax output layer for classification.

Key features of the model:

- **Convolutional Layers**: For feature extraction.
- **Pooling Layers**: For downsampling.
- **Fully Connected Layers**: For classification.
- **Softmax Layer**: For generating probability distributions over classes.

## Results

The trained model achieves high accuracy in classifying various hand gestures. The performance is evaluated using accuracy, precision, recall, and F1-score metrics.
