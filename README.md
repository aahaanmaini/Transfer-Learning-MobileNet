# Transfer Learning with MobileNetV2 🐶🐱

This project implements a transfer learning pipeline using the MobileNetV2 architecture pretrained on ImageNet, adapted to classify a custom dataset of cats and dogs. The notebook demonstrates both feature extraction and fine-tuning to achieve improved accuracy.

---

## Features
- Uses MobileNetV2 with pretrained ImageNet weights
- Adds custom classification head for binary classification
- Applies data augmentation (flipping, rotation, zoom, translation)
- Trains in two stages: frozen base model and fine-tuned top layers
- Evaluates performance before and after fine-tuning

---

## Technologies Used
- **Python 3.x**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **scikit-learn**

---

## Dataset
- Binary classification: **Cats vs. Dogs**
- Dataset loaded via `image_dataset_from_directory`
- Images resized to 160×160

---

Made with 💻 and 🧠 for deep learning practice using transfer learning.
