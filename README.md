# Agrobot - Teachable Machine Web Classifier

This project is a lightweight website that uses a **Teachable Machine** image classification model to recognize different objects through the webcam.

1. How it works

1.1. The model is loaded directly from Teachable Machine using TensorFlow.js.
1.2. Once the user clicks **Start**, the webcam activates and starts predicting based on the trained model.
1.3. Predictions are displayed in real time with their corresponding probability.

2. Model

The model was trained using [Teachable Machine](https://teachablemachine.withgoogle.com/) and is designed to identify specific objects related to our prototype, **Agrobot**.

## Files

- `index.html`: Main web page that loads the model and handles everything.

## Webcam Note

The site may ask for permission to access the webcam. Make sure to allow it for full functionality.

## Authors

This website was developed as part of the **Agrobot project** for the [BIEA STEM Youth Innovation Competition].
