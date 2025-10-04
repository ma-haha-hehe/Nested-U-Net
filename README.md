This project implements a UNet++ (Nested U-Net) model to perform cell segmentation on medical imaging datasets.
UNet++ extends the classical U-Net by introducing dense skip connections and nested convolutional blocks, which effectively reduce the semantic gap between encoder and decoder feature maps.

By leveraging these architectural improvements, the model achieves more accurate boundary localization and higher segmentation performance for complex cellular structures.
The implementation supports various medical image preprocessing methods, data augmentation, and visualization of predicted segmentation masks.

Key Features

·UNet++ architecture with deep supervision
·Supports medical cell image datasets
·Integrated data preprocessing and augmentation pipeline
·Training and validation implemented in PyTorch
·Visualization tools for segmentation results and evaluation metrics
