# 😷 Face Mask Detector

The Face Mask Detector is an AI-powered web application that helps detect whether a person is wearing a face mask, aimed at supporting health safety measures during the COVID-19 pandemic. The model identifies two categories: "mask" and "no-mask." It uses TensorFlow.js to run a machine learning model directly in the browser, making it accessible and easy to deploy in various environments.

![Face Mask Detector](https://github.com/yerin16/face-mask-detector/blob/main/images/preview.png?raw=true)


## Table of Contents

- [Features](#features)
- [File Structure](#file-structure)
- [How it works](#how-it-works)

## Features

- **Real-Time Detection:** The model uses a webcam to detect if a person is wearing a mask.
- **Accuracy:** Trained with a machine learning model to distinguish between "mask" and "no-mask" conditions.
- **User-Friendly Interface:** The web app is built with a responsive layout using HTML, CSS, and Bootstrap for a simple, clear interface.
- **Visual and Audio Alerts:** Alerts are triggered if a mask is not detected, encouraging proper mask usage.

## File Structure
- **index.html:** Main web page for the face mask detector interface(index).
- **style.css:** Contains styling for the user interface(style).
- **model.json:** TensorFlow.js model configuration file(model).
- **metadata.json:** Metadata for the model, including labels for mask detection(metadata).

## How It Works

1. The user clicks "Start" to activate the webcam.
2. The webcam captures live video, and the model runs predictions to detect if a mask is present.
3. Based on the result, the app provides real-time feedback by showing either "Good Job!" or "MASK ON Please" depending on whether a mask is detected.
4. The interface displays the predicted probabilities for both "mask" and "no-mask" cases.