# Malaria Detection using CNN (96% Accuracy)

This project aims to detect malaria in cell images using a Convolutional Neural Network (CNN). The model was trained on the **"Cell Images for Detecting Malaria"** dataset and achieved a **96% accuracy** on the validation set. The dataset consists of two categories: `Parasitized` (infected cells) and `Uninfected` (healthy cells).

## Project Overview
- **Dataset**: Cell images are split into two classes: `Parasitized` (malaria-infected cells) and `Uninfected`.
- **Model Architecture**: A CNN model was built using multiple convolutional layers, max-pooling layers, and dropout layers to avoid overfitting.
- **Training**: The model was trained using `ImageDataGenerator` for data augmentation and an early stopping mechanism to prevent overfitting.
- **Performance**: The model achieved 96% accuracy on the test data.
The dataset consists of:
- **Parasitized**: Images of infected cells. ![36d6029f-ae5d-45b6-b452-b4effd01d995](https://github.com/user-attachments/assets/f9bea5bf-8a31-4208-9d67-17b49f4f1781)

- **Uninfected**: Images of uninfected cells.

  
