
# Deep Learning Image Classification with Attention and Pretrained Models

This project implements a deep learning pipeline for image classification using modified VGG16 and Xception architectures with multi-head attention mechanisms. The dataset for training and evaluation is sourced from Kaggle, enabling robust and high-performance image recognition.

The project focuses on classifying images into three categories using state-of-the-art transfer learning techniques. The models incorporate:

Pre-trained backbones (VGG16 and Xception) to leverage existing image feature extraction capabilities.
Multi-Head Attention for enhanced focus on specific image regions.
Techniques like Batch Normalization, Gaussian Noise, and Dropout for improved regularization and generalization.

Dataset
The dataset used for this project is publicly available on Kaggle. Ensure you download it and organize the files appropriately for the data generator to locate:

Train images: Images used to train the model.
Validation images: Images for hyperparameter tuning.
Test images: Images for model evaluation.

## Features

- Data Augmentation using ImageDataGenerator
- Two Modified Architectures:

   - VGG16 with attention and dense layers.

   - Xception with similar enhancement
- Custom Training Pipelines:

   - Efficient handling of train, validation, and test splits.
    
   - Augmented image pre-processing for normalization.
- Attention Mechanism to boost the model's focus on important regions.
- Performance metrics like accuracy, confusion matrix, and classification report.



## Installation

Install this notebook with git

```bash
git clone https://github.com/barrysarthak/<repo_name>.git
cd <repo_name>

```
    
