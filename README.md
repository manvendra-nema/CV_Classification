# 🖼️ Image Classification Project

Welcome to the **Image Classification Project**! This tutorial explores various aspects of image classification using convolutional neural networks (CNNs), covering data preparation, model training, evaluation, and analysis to understand the classification process.

## 🔍 Task Overview

### 0. 📊 Data Preparation
   - Download the [SVHN Dataset (Format 2)](http://ufldl.stanford.edu/housenumbers/) and split it into train, validation, and test sets.
   - Visualize the data distribution across class labels for training and validation sets.

### 1. 🏗️ Training a CNN from Scratch
   - Design and implement a CNN architecture with 2 Convolution Layers.
   - Train the model using Cross-Entropy Loss and ReLU activation functions.
   - Log training and validation metrics using [Weights & Biases (WandB)](https://docs.wandb.ai/quickstart).
   - Evaluate model performance on the test set, report Accuracy, F1-Score, and visualize the confusion matrix.
   - Analyze misclassifications and their possible reasons.

### 2. 🔧 Fine-tuning a Pretrained Model
   - Fine-tune a ResNet-18 architecture pretrained on ImageNet.
   - Log training and validation metrics using [Weights & Biases (WandB)](https://docs.wandb.ai/quickstart).
   - Evaluate model performance on the test set, report Accuracy, F1-Score, and visualize the confusion matrix.
   - Visualize feature representations using [t-SNE plots](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html) in 2D and 3D space.

### 3. 🖼️ Data Augmentation Techniques
   - Apply data augmentation techniques suitable for image classification tasks.
   - Train models using augmented data and evaluate performance metrics.
   - Report Accuracy, F1-Score, and visualize the confusion matrix.

### 4. 🔍 Misclassification Analysis
   - Analyze misclassified images using Euclidean distances in feature space.
   - Compare distances from ground truth class centroids to predicted class centroids across models.

### 5. 📊 Model Comparison
   - Compare and comment on the performance of all three models.

## 🌟 Highlights
- **Misclassification Analysis:** Gain insights into why models misclassify certain images.
- **t-SNE Visualization:** Explore feature representations in 2D and 3D space to understand data clustering.

Stay tuned for updates and insights as we progress through the project!

## 📊 Data Visualization 

![Data Distribution](https://github.com/manvendra-nema/CV_Classification/assets/53614640/7f6818cb-530f-4e16-982f-6326cc62e786)

## 2-D t-SNE

![2-D t-SNE](https://github.com/manvendra-nema/CV_Classification/assets/53614640/3fe55285-a802-4d8d-8024-873bbc9df725)

## 3-D t-SNE

![3-D t-SNE](https://github.com/manvendra-nema/CV_Classification/assets/53614640/d5ab2a4b-ff72-48c2-ac4f-938fa558a9ff)

## 🔄 Misclassification

![Misclassification](https://github.com/manvendra-nema/CV_Classification/assets/53614640/a3ac9ef9-ef49-447c-8dc5-b329a52ff585)

---
