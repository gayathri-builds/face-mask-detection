# 😷 Face Mask Detection – Deep Learning Project

## 📌 Project Overview

This project involves building a **Face Mask Detection** model using computer vision techniques to classify whether a person is wearing a mask or not in real-time. The system uses a Convolutional Neural Network (CNN) trained on labeled images and can be integrated into surveillance systems for public health monitoring.


## 🧾 Dataset

- **Source:** [Kaggle – Face Mask Dataset](https://www.kaggle.com/datasets) or custom collected dataset  
- **Classes:**  
  - With Mask  
  - Without Mask  
- **Images:** Preprocessed and augmented for better generalization


## ⚙️ Tools & Technologies

- **Language:** Python  
- **Libraries:** TensorFlow / Keras, OpenCV, NumPy, Matplotlib, Scikit-learn  
- **Model:** Convolutional Neural Network (custom or MobileNetV2)


## 🔍 Workflow

1. **Data Preparation**
   - Loaded and resized images
   - Label encoding and data augmentation using ImageDataGenerator

2. **Model Building**
   - Built a CNN from scratch (or used MobileNetV2 as a base model)
   - Added dropout and batch normalization layers

3. **Training**
   - Compiled using `Adam` optimizer and `binary_crossentropy` loss
   - Trained with early stopping and validation monitoring

4. **Evaluation**
   - Plotted accuracy/loss curves
   - Confusion matrix and classification report

5. **Deployment (Optional)**
   - Real-time mask detection using webcam and OpenCV  
   - Integrated model with live video feed


## 📈 Results

- **Training Accuracy:** ~98%  
- **Validation Accuracy:** ~95%  
- **Inference Speed:** Real-time on webcam (~30 FPS on CPU)
