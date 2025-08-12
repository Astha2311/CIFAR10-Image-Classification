# CIFAR-10 Image Classification using CNN

This project implements a Convolutional Neural Network (CNN) to classify images from the **CIFAR-10** dataset, which contains 60,000 32x32 color images across 10 classes such as airplanes, cars, birds, and more.

---

## 📌 Objectives
- Apply deep learning techniques for image classification.
- Train a CNN model on CIFAR-10 using TensorFlow/Keras.
- Evaluate model performance and accuracy.

---

## 🛠 Methodology
1. **Dataset**: CIFAR-10 dataset (50,000 training images + 10,000 test images).
2. **Preprocessing**:
   - Normalized pixel values to [0, 1].
   - One-hot encoded labels.
3. **Model Architecture**:
   - Multiple convolutional + max pooling layers.
   - Fully connected dense layers.
   - Softmax activation for classification.
4. **Training**:
   - Optimizer: Adam
   - Loss: Categorical Crossentropy
   - Epochs: 3 (for demo purposes)
5. **Evaluation**:
   - Achieved ~72% validation accuracy in just 3 epochs.

---

## 📊 Results
- **Validation Accuracy**: ~72%
- **Test Accuracy**: ~71%
- Model shows good performance for a simple architecture and short training.

---

## 📂 Files in Repository
- `Untitled10.ipynb`: Google Colab notebook containing:
  - Report text
  - CNN code
  - Training & evaluation results
- `cifar10_model.h5`: *(Optional)* Saved trained model file.

---

## 🚀 Future Improvements
- Train for more epochs.
- Apply data augmentation.
- Use transfer learning with pretrained models (ResNet, MobileNetV2).

---

## 📜 License
This project is for academic purposes and

