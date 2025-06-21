# Handwritten Character Classification with CNN & Residual Blocks

This project presents a deep learning pipeline to classify handwritten alphabetic characters using a custom convolutional neural network (CNN) enhanced with residual blocks, inspired by ResNet architecture. The model is trained and evaluated on image data stored in CSV format, each representing a 28x28 grayscale image.

* `Training.ipynb` – Contains the complete model architecture, data processing pipeline, training routines, and model saving logic.
* `Testing.ipynb` – Loads the trained model and evaluates its performance on test data, with visualizations like confusion matrices and class-level accuracy.

## Model Architecture

* Built using PyTorch
* Residual blocks to combat vanishing gradients and enable deeper learning
* Batch normalization and dropout for better generalization
* Adaptive average pooling and fully connected output layer

## Dataset

* CSV-based dataset with pixel values and corresponding character labels
* Preprocessing includes grayscale conversion, normalization

## Metrics & Visualization

* Confusion Matrix
* Per-class accuracy
* Loss & accuracy plots over epochs
* Visual model architecture using `torchviz` and `torchsummary`

## 💡 Highlights

* Custom PyTorch dataset class for efficient CSV handling
* Modular and reusable CNN + residual block design
* Easy integration with other image datasets of similar shape

---
