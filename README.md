This project builds a convolutional neural network to classify MRI images for brain tumor detection with high accuracy.

### 🔍 Overview
- Developed a **ResNet-50–based CNN** trained on brain MRI scans  
- Achieved **97% accuracy** on the test set  
- Optimized training with the **Adam** optimizer and data augmentation  
- Used PyTorch for model development, training loops, and evaluation

### 🛠️ Tech Stack
- **Python**
- **PyTorch**
- **NumPy**, **Matplotlib**
- **OpenCV / PIL** for image preprocessing

### 📁 Key Steps
1. Loaded and preprocessed MRI image dataset  
2. Applied augmentation (rotation, normalization, resizing)  
3. Fine-tuned a pretrained **ResNet-50**  
4. Trained using Adam + cross-entropy loss  
5. Evaluated model performance with accuracy and confusion matrix  

### 📊 Results
- **97% classification accuracy**
- Strong generalization across tumor vs non-tumor classes
- Useful for medical-imaging-based decision support
