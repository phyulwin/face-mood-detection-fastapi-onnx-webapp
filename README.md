## Mood Detection Web App

A real-time facial emotion recognition web application powered by an ONNX model and FastAPI backend. Detect emotions such as happy, sad, angry, and more using your webcam or by uploading an image.

![App Screenshot](static/screenshots/Screenshot%202025-07-19%20145345.png)

### Model Used

This application uses the [opencv/facial_expression_recognition](https://huggingface.co/opencv/facial_expression_recognition) ONNX model from Hugging Face:

- Architecture: MobileNetV2
- Trained on: FER-2013 dataset
- Output: Seven emotion classes — angry, disgust, fear, happy, neutral, sad, surprise

---

## Features

- Real-time webcam emotion detection
- Image upload and analysis
- Emotion confidence scores
- Powered by ONNX and FastAPI
- Modern user interface built with HTML, CSS, and JavaScript

---

## Emotion Labels

The application detects the following emotions:

- Angry
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Surprise

---

## Screenshots

![Screenshot 1](static/screenshots/Screenshot%202025-07-19%20145650.png)
![Screenshot 2](static/screenshots/Screenshot%202025-07-19%20145801.png)

---

## Credits

- [OpenCV on Hugging Face](https://huggingface.co/opencv) for the ONNX model
- [FastAPI](https://fastapi.tiangolo.com/) for the backend
- [Pillow](https://pillow.readthedocs.io/) and [ONNX Runtime](https://onnxruntime.ai/) for model inference

