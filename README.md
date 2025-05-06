# 🐶🐱 Cat vs Dog Image Classifier

This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images of cats and dogs. Built as part of the [freeCodeCamp Machine Learning Certification](https://www.freecodecamp.org/).

## 🎯 Objective
Train a CNN model that can classify cat and dog images with over 63% accuracy.

## 📊 Dataset
The dataset is provided by freeCodeCamp and includes:
- 2,000 training images
- 1,000 validation images
- 50 test images (unlabeled)

The folder structure:
cats_and_dogs/
├── train/
│ ├── cats/
│ └── dogs/
├── validation/
│ ├── cats/
│ └── dogs/
└── test/
└── [unlabeled images]


## 🧪 Model Summary
- Preprocessing with `ImageDataGenerator` (rescaling + augmentation)
- CNN with Conv2D, MaxPooling2D, and Dense layers
- Trained for 15 epochs with a batch size of 128

## 📈 Results
- Achieved over **63% accuracy**
- Successfully passed the automated test
- Visualized predictions on test data

## 🛠 Tools Used
- Python 3.x
- TensorFlow 2.x
- Keras
- Google Colab
- Matplotlib & NumPy

## 🚀 How to Run
1. Open the `.ipynb` notebook in Google Colab.
2. Run all cells in order.
3. Make sure the dataset downloads and unzips correctly.
4. After training, evaluate and visualize predictions in Cells 10 & 11.

---

🎓 **Project completed as part of freeCodeCamp Machine Learning Certification.**

