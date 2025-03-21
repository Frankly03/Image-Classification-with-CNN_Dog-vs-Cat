# Image Classification with CNN - Dog vs Cat

## Overview
This project focuses on classifying images of dogs and cats using Convolutional Neural Networks (CNNs). The goal is to compare the performance of a **custom CNN model built from scratch** with a **pre-trained ResNet18 model** using transfer learning. The project demonstrates the end-to-end process of data preprocessing, model development, training, and evaluation.

## Tools and Technologies
- Python
- PyTorch
- CNN
- NumPy
- Matplotlib

## Key Steps
1. **Data Preprocessing**:  
   - Resized and augmented images using PyTorch to improve model generalization.  
   - Loaded the dataset using Kaggle API for seamless integration.  

2. **Model Development**:  
   - Built a **custom CNN model from scratch** with multiple convolutional and pooling layers.  
   - Fine-tuned the **ResNet18 pre-trained model** using transfer learning.  

3. **Training and Evaluation**:  
   - Trained both models on the training dataset and evaluated their performance on a test dataset.   

4. **Visualization**:  
   - Generated visualizations such as accuracy/loss curves to analyze model performance.  

## How to Run the Code
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Image-Classification-CNN-Dog-vs-Cat.git


2. Run the Jupyter Notebook or Python script to train and evaluate the models.

## Results:

Custom CNN Model Accuracy: **94%**

ResNet18 Model Accuracy: **97%**


# Visualizations

## Loss Curve and Accuracy Curve plot of Custom Model
![Loss Curve of Custom model](images/customModel.png)

## Loss Curve and Accuracy Curve plot of Resnet18 model
![Loss Curve of Resnet18 model](images/Resnet18.png)

## Prediction on Resnet18 Model
![Prediction using Resnet18 model](images/Prediction.png)

