# Face Mask Classification using Deep Learning

A deep learning project for binary face mask classification using Transfer Learning with a pre-trained ResNet50 model. The project evaluates multiple training configurations and improvement strategies to achieve robust and accurate face mask detection.

---

## Project Overview

This project develops a binary image classification system capable of determining whether a person is wearing a face mask or not.

A pre-trained ResNet50 model was used as the backbone network through Transfer Learning. Extensive experiments were conducted to evaluate the impact of different hyperparameters, image preprocessing techniques, loss functions, regularization methods, and optimization strategies.

---

## Features

- Binary Face Mask Classification
- Transfer Learning with ResNet50
- Hyperparameter Tuning
- Fine-Tuning Experiments
- Performance Evaluation
- Confusion Matrix
- ROC Curve
- Precision, Recall & F1-Score Analysis
- Training & Validation Curves

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- OpenCV

---

## Dataset

**Face Mask 12K Images Dataset**

- Total Images: **11,792**
- Classes:
  - With Mask
  - Without Mask

Dataset split:

- Training
- Validation
- Testing

---

##  Model

The project uses **Transfer Learning** based on a pre-trained **ResNet50** model.

### Baseline Configuration

- Frozen ResNet50 feature extractor
- Softmax output layer
- Adam Optimizer
- Learning Rate = 0.001
- Batch Size = 32
- Early Stopping
- Model Checkpoint

---

## Experiments

The project investigates several improvement techniques including:

### Hyperparameter Experiments

- Different sample sizes
- Different learning rates
- Different numbers of epochs

### Regularization

- Batch Normalization
- Dropout
- L2 Regularization

### Image Processing

- Low Resolution
- High Resolution
- Grayscale Images

### Loss Functions

- Cross Entropy
- Focal Loss
- Label Smoothing
- Class Weighted Loss

### Optimization Strategies

- Stochastic Gradient Descent (SGD)
- Mini-Batch Gradient Descent
- Full-Batch Gradient Descent

---

## Best Results

| Metric | Value |
|---------|-------|
| Test Accuracy | **98.89%** |
| Test Loss | **0.0312** |
| AUC | **0.9993** |
| Precision | **0.9889** |
| Recall | **0.9889** |
| F1-Score | **0.9889** |

---

## Evaluation Metrics

- Accuracy
- Loss
- Precision
- Recall
- F1-Score
- ROC Curve
- Confusion Matrix

---

## Repository Structure

```
├── README.md
├── Face_Mask_Classification.ipynb
└── report.pdf
```

---

## Learning Outcomes

- Deep Learning
- Transfer Learning
- Computer Vision
- Image Classification
- Hyperparameter Tuning
- Fine-Tuning
- Model Evaluation
- Deep Learning Optimization

---

## Team

- Noran Aljodi
- Rema Althaqfi
- Enas Althyabi
- Asail Al-Osaimi
- Reema Alharbi

---

## License

This project was developed for academic purposes.
