Implemented a **Convolutional Neural Network (CNN)** to classify histopathologic images of cancerous tissue with high accuracy.

---

## Overview
- Developed a CNN model for classifying histopathologic images
- Achieved competitive accuracy in distinguishing cancerous vs. normal tissue
- Preprocessed images: resizing, normalization, and augmentation
- Split dataset into training, validation, and test sets
- Used **PyTorch** for model development, training, and evaluation

---

## Tech Stack
- **Python**
- **PyTorch / Torchvision**
- **NumPy, Pandas, Matplotlib, Seaborn**
- **OpenCV / PIL** for image preprocessing
- **TensorBoard** for training visualization

---

## Key Steps

### 1. Data Loading & Exploration
- Loaded histopathologic image dataset
- Explored image shapes, class distribution, and sample images

### 2. Image Preprocessing
- Resized images to a uniform size
- Normalized pixel values to standard range
- Applied data augmentation: rotations, flips, color jitter

### 3. Visualization
- Displayed sample cancerous and normal tissue images
- Visualized class distribution
- Generated feature maps from intermediate CNN layers

### 4. Model Development
- Designed a CNN with convolutional, pooling, and fully connected layers
- Used **ReLU activation** and **dropout** for regularization
- Output layer with **sigmoid activation** for binary classification
- Optimized using **binary crossentropy loss** and **Adam optimizer**

### 5. Training & Evaluation
- Trained model on training set, validated on validation set
- Monitored accuracy and loss curves during training
- Evaluated performance using **confusion matrix**, **ROC curve**, and **classification report**

### 6. Testing & Deployment
- Tested model on unseen histopathologic images
- Generated predictions ready for research or clinical applications

---

## Results
- Model achieves strong accuracy in detecting cancerous tissue
- Confusion matrix confirms robust class separation
- CNN visualizations provide insights into important features

---
