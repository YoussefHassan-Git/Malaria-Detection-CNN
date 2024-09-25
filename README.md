# 🦠 Malaria Detection using CNN (96% Accuracy) 

Malaria is a life-threatening disease caused by parasites transmitted through the bites of infected female Anopheles mosquitoes. Timely and accurate diagnosis is crucial in treating the disease, especially in resource-limited regions. This project uses a CNN-based deep learning approach to automatically detect malaria-infected cells from microscopic images of blood samples.

This project aims to detect malaria in cell images using a **Convolutional Neural Network `(CNN)`**. The model was trained on the **"Cell Images for Detecting Malaria"** dataset and achieved a **96% accuracy** on the validation set. The dataset consists of blood smear images of parasitized and uninfected cells, which are processed and analyzed to classify them as either **infected or healthy**. The model is trained using TensorFlow and Keras on the Cell Images dataset from Kaggle.

## 📚 Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Dataset Structure](#dataset-structure)
- [Data Preprocessing](#data-preprocessing)
- [Model Performance](#model-performance)
- [Sample Images](#sample-images)
  - [Parasitized Cells](#sample-of-parasitized)
  - [Uninfected Cells](#sample-of-uninfected)
- [Model Architecture Diagram](#model-architecture-diagram)
- [Training and Validation Graphs](#training-and-validation-graphs)
- [Example Testing The Model](#example-testing-the-model)

---

## 🛠️ Project Overview

- **Dataset**:
  * The dataset used for training and testing the model is publicly available on Kaggle. It contains 27,558 images of parasitized and uninfected cells, divided into two categories:
    Cell images are split into two classes: `Parasitized` (malaria-infected cells) and `Uninfected`.
  
- **Model Architecture**:
  * A CNN model was built using multiple convolutional layers, max-pooling layers, and dropout layers to avoid overfitting.
  
- **Training**:
  * The model was trained using `ImageDataGenerator` for data processing and an early stopping mechanism to prevent overfitting.

---

## 📁 Dataset Structure:

- **Parasitized**: 13.8k images
- **Uninfected**: 13.8k images

These images are pre-processed and split into **training and testing datasets**, with an 80-20 ratio.

---

## ⚙️ Data Preprocessing:

- Images are resized to 150x150 pixels.
- Normalization is applied by scaling pixel values between 0 and 1.

---

## 🏗️ Model Architecture

- **Convolutional Layers**: Several convolutional layers to extract features from the images.
- **Max Pooling Layers**: Used to reduce spatial dimensions.
- **Dropout Layers**: Included to prevent overfitting.

![Model Architecture Diagram](https://github.com/user-attachments/assets/047565f8-4adc-4893-b8ce-b8c0acb822bc)

---

## 📈 Model Performance

The model achieved **96% accuracy** on the test data, with the following performance metrics:

- **Training Accuracy**: ~96%
- **Validation Accuracy**: ~95%
- **Testing Accuracy**: ~96%

---

## 📊 Training and Validation Graphs

**Training, Validation Loss Graph:**

![Training, Validation Loss Graph](https://github.com/user-attachments/assets/f4bf59ad-4405-47d9-89a8-f187a78e4797)

**Training, Validation Accuracy Graph:**

![Training, Validation Accuracy Graph](https://github.com/user-attachments/assets/986bf58a-d392-4d95-92ef-6707bde47430)

---

## 📷 Sample Images

### 🦠 Sample of Parasitized:

![Sample of Parasitized Cells](https://github.com/user-attachments/assets/f9bea5bf-8a31-4208-9d67-17b49f4f1781)

### 🚫 Sample of Uninfected:

![Sample of Uninfected Cells](https://github.com/user-attachments/assets/6631bd28-7245-4b93-b883-f5e94fb2e88a)

---

## 🧪 Example Testing The Model

Here is an example of testing the model with a random sample from the test set:

![Example Testing The Model](https://github.com/user-attachments/assets/95dc2d1f-c9bd-40a6-ab78-d47dc0ad6d3b)

---
