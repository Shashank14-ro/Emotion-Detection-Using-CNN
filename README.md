# Emotion-Detection-Using-CNN
A deep learning project for facial emotion detection using Convolutional Neural Networks (CNN). Trained on datasets like FER2013 with real-time emotion recognition support.

This project performs facial emotion detection using Convolutional Neural Networks (CNN). It can identify emotions like Happy, Sad, Angry, Surprise, etc., from real-time webcam input or images.

## 📌 Features
- Facial emotion recognition using CNN
- Trained on FER2013 dataset
- Real-time emotion detection via webcam (OpenCV)
- Supports live prediction with bounding box and emotion label

## 🧠 Technologies
- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Matplotlib

## 🗃 Dataset
- [FER2013](https://www.kaggle.com/datasets/msambare/fer2013)

## 🚀 Getting Started

### Clone Repo
```bash
git clone https://github.com/your-username/emotion-detection-cnn.git
cd emotion-detection-cnn
```
Install Requirements
  ```pip install -r requirements.txt```
 Train Model
   python src/train.py
 Run Real-Time Detection
     python main.py
```
📁 Suggested Project Structure
plaintext
Copy
Edit
emotion-detection-cnn/
├── dataset/               # Folder for training/testing data or CSV links
├── models/                # Saved models (.h5, .pt)
├── notebooks/             # Jupyter notebooks for training/experiments
├── src/                   # Python scripts for training, prediction, utils
│   ├── train.py
│   ├── model.py
│   └── predict.py
├── haarcascades/          # For face detection (OpenCV XML files)
├── requirements.txt       # Python dependencies
├── README.md
├── .gitignore
└── main.py                # Real-time emotion detection script
