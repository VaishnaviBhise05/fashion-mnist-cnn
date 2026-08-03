# Fashion-MNIST CNN Classifier

A Convolutional Neural Network (CNN) built with TensorFlow/Keras to classify clothing images from the Fashion-MNIST dataset into 10 categories (e.g. T-shirt, Trouser, Sneaker, Bag, etc.).

## 📌 Overview
This project trains a CNN on the Fashion-MNIST dataset, which contains 70,000 grayscale images (28x28 pixels) of clothing items across 10 classes.

## 🗂️ Dataset
- **Source:** `tensorflow.keras.datasets.fashion_mnist`
- **Training samples:** 60,000
- **Test samples:** 10,000
- **Image size:** 28x28 grayscale
- **Classes:** 10 (T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot)

## 🏗️ Model Architecture
- Conv2D + MaxPooling2D layers for feature extraction
- Flatten layer
- Dense (fully connected) layers
- Softmax output layer for 10-class classification

## ⚙️ Tech Stack
- Python
- TensorFlow / Keras
- Matplotlib (for visualization)

## 🚀 How to Run
```bash
pip install tensorflow matplotlib
python fashion_mnist_2124udsf1006_.py
```

## 📊 Results
- Achieved test accuracy of **~XX%** after training for 10 epochs.
- Used EarlyStopping callback to prevent overfitting.

## 📁 Files
- `fashion_mnist_2124udsf1006_.py` — Main script containing data preprocessing, model building, training, and evaluation.

## 🔮 Future Improvements
- Add dropout layers to reduce overfitting
- Experiment with deeper architectures
- Add confusion matrix and per-class accuracy metrics
