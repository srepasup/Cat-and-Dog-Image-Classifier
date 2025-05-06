# 🐶🐱 Cat vs Dog Image Classifier 

![Model Accuracy](https://img.shields.io/badge/accuracy-70%25-brightgreen)
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/15/2010-kodiak-benny.jpg/640px-2010-kodiak-benny.jpg" alt="Cat and Dog" width="600"/>

This project uses a Convolutional Neural Network(CNN) built with Keras and TensorFlow 2.0 to classify images as either a cat or a dog. It uses a dataset of 3,000+ labeled images and achieves over 70% accuracy.

✅ Trained on 2,000 images  
✅ Validated on 1,000 images  
✅ Tested on 50 unlabeled images  

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


