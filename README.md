# Brain Wave Classification from EEG Using Machine Learning and Deep Learning


## Course: 499B and 499A

### Group: 7

### Members: 
- Sumaiya Binte Sultana (2021612642)  
- Fatema (2021612642)  
- Jubair Hossain (2021626642)  

## Project Overview
This project aims to develop an EEG (Electroencephalogram) classification system using **Convolutional Neural Networks (CNNs)** to analyze EEG signals and classify them into predefined categories. The model processes EEG data, learns patterns from the signal features, and outputs a classification result, which can be used for various applications such as mental state monitoring, neurological disease detection, or brain-computer interfaces.

The system is built with **PyTorch**, a popular deep learning framework, and is designed to handle EEG data with a channel size of 14 and signal length of 224.

## Methodology

### CNN Model Architecture
- Custom-built convolutional neural network with layers optimized for EEG signal processing.

### Data Processing
- Input EEG signals are processed through multiple convolutional layers for feature extraction.

### Classification
- The model classifies EEG data into one of the multiple classes based on the learned features.

### Training and Evaluation
- The model is trained using a **Cross-Entropy Loss** function and optimized using the **Adam optimizer**.

### Validation
- The system includes a validation loop to evaluate model performance during training.

### Dropout Regularization
- Dropout layers to prevent overfitting and improve generalization.
