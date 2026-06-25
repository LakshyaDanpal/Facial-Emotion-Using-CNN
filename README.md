# 😊 Facial Emotion Detection using CNN

A deep learning-based Facial Emotion Detection system built using a Convolutional Neural Network (CNN) and TensorFlow/Keras. The model classifies facial expressions into seven different emotions from grayscale facial images.

## 📌 Project Overview

This project uses a Convolutional Neural Network (CNN) to recognize human emotions from facial images. The model is trained on labeled emotion datasets and predicts one of seven emotions from a given face image.

### Supported Emotions

- 😠 Angry
- 🤢 Disgust
- 😨 Fear
- 😀 Happy
- 😢 Sad
- 😲 Surprise
- 😐 Neutral

---

## 🚀 Features

- Image preprocessing and normalization
- CNN architecture for emotion classification
- Training, validation, and testing pipeline
- Early Stopping to reduce overfitting
- Model saving and loading
- Emotion prediction on new images
- Accuracy and loss visualization

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn

---

## 📂 Project Structure

```
Emotion-Detection/
│
├── images/
│   ├── train/
│   │   ├── Angry/
│   │   ├── Disgust/
│   │   ├── Fear/
│   │   ├── Happy/
│   │   ├── Sad/
│   │   ├── Surprise/
│   │   └── Neutral/
│   │
│   └── test/
│       ├── Angry/
│       ├── Disgust/
│       ├── Fear/
│       ├── Happy/
│       ├── Sad/
│       ├── Surprise/
│       └── Neutral/
│
├── model/
│   └── emotion_detection_model.h5
│
├── cnn.ipynb
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/emotion-detection.git
```

Move into the project directory:

```bash
cd emotion-detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 📦 Required Libraries

```text
tensorflow
keras
numpy
opencv-python
matplotlib
scikit-learn
```

Or install manually:

```bash
pip install tensorflow keras numpy opencv-python matplotlib scikit-learn
```

---

## ▶️ Running the Project

Launch the Jupyter Notebook:

```bash
jupyter notebook cnn.ipynb
```

Run all cells sequentially.

The notebook will:

1. Load the dataset
2. Preprocess images
3. Build the CNN model
4. Train the model
5. Evaluate performance
6. Save the trained model
7. Predict emotions on test images

---

## 🧠 CNN Architecture

The model consists of:

- Convolutional Layers
- ReLU Activation
- Max Pooling Layers
- Dropout Layers
- Flatten Layer
- Fully Connected Dense Layers
- Softmax Output Layer (7 Classes)

---

## 📊 Model Training

The training pipeline includes:

- Image normalization
- Train-validation split
- Adam Optimizer
- Categorical Crossentropy Loss
- EarlyStopping Callback

---

## 📈 Evaluation

The notebook visualizes:

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss

The model is evaluated on the test dataset after training.

---

## 💾 Model Saving

After training, the model is saved as:

```
model/emotion_detection_model.h5
```

This model can later be loaded for prediction without retraining.

---

## 🔮 Prediction

The trained model predicts the emotion of an input face image and returns one of the seven emotion classes.

Example:

```
Predicted Emotion: Happy 😀
```

---

## 📌 Future Improvements

- Real-time emotion detection using webcam
- Transfer Learning (ResNet, MobileNetV2)
- Data augmentation
- Improve model accuracy
- Deploy as a web application using Flask or Streamlit

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Submit a Pull Request.

---

## 📄 License

This project is intended for educational and research purposes.

---

## 👨‍💻 Author

**Lakshya Setty**

Information Science Engineering

Deep Learning | Machine Learning | Computer Vision
