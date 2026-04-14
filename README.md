# 🐶🐱 Image Classification Cats vs Dogs 

## 📌 Project Overview

This project is a deep learning-based image classification system that can distinguish between cats and dogs.
It uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

---

## 🚀 Features

* Classifies images as **Cat 🐱** or **Dog 🐶**
* Built using CNN (Deep Learning)
* Supports custom image prediction
* Works on Google Colab
* Easy to train and extend

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Google Colab

---

## 📂 Dataset Structure

dataset/cats
dataset/dogs

* Each folder contains images of respective classes
* Dataset should be balanced for better accuracy


## ▶️ How to Run

1. Mount Google Drive (if using Colab)

2. Load dataset using:
   tf.keras.utils.image_dataset_from_directory()

3. Train the model:
   model.fit(...)

4. Predict new images:

* Upload image
* Run prediction script

---

## 🧠 Model Details

* Input size: 150x150 images
* Architecture:

  * Conv2D + MaxPooling
  * Dense layers
* Activation: ReLU, Sigmoid
* Loss Function: Binary Crossentropy
* Optimizer: Adam

---

## 📊 Results

* Accuracy: ~80–90% (depending on dataset size)
* Performance improves with more data and augmentation

---

## 📸 Example Prediction

Input: Image
Output: "Cat 🐱" or "Dog 🐶"

---

## 🔮 Future Improvements

* Use Transfer Learning (e.g., MobileNet, VGG16)
* Improve accuracy with larger dataset
* Deploy as web app
* Add real-time camera detection

## 👨‍💻 Author

Vishnu R
