# **Animal Faces Classification with PyTorch**  

This project implements a **deep learning-based image classification model** using **PyTorch** to classify images into three categories: **Cats, Dogs, and Wildlife**. The dataset used is **Animal Faces-HQ (AFHQ)**, which contains **16,130 high-quality images** of animals at **512×512 resolution**.  

## **Dataset**  
The dataset consists of three classes:  
- **Cat**  
- **Dog**  
- **Wildlife**  

Each class contains around **5,000 images**, making it a balanced dataset for training deep learning models.  

## **Model Architecture**  
The model is a **Convolutional Neural Network (CNN)** built using `torch.nn.Sequential`. It consists of:  
- **Three convolutional layers** (`Conv2d`) with ReLU activation and max pooling.  
- **A fully connected (FC) layer** for classification.  
- **Softmax output layer** to predict one of the three classes.  

## **Training Details**  
- **Optimizer:** Adam  
- **Loss Function:** CrossEntropyLoss  
- **Batch Size:** Customizable  
- **Evaluation Metrics:** Accuracy and Loss  

## **How to Use**  
1. Load the dataset and apply transformations (resize, normalization, etc.).  
2. Train the model using the provided training loop.  
3. Evaluate performance on the validation set.  
