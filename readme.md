# Dog Detection Using TensorFlow Hub SSD Model

This project uses an SSD-based object detection model from TensorFlow Hub to detect dogs in images. The model is pre-trained on the Open Images V4 dataset and uses MobileNet V2 (pre-trained on ImageNet) as the image feature extractor.

## Model Overview

- **Model Used:** SSD (Single Shot MultiBox Detector)
- **Feature Extractor:** MobileNet V2 (pre-trained on ImageNet)
- **Training Data:** Dog image dataset
- **Source:** [TensorFlow Hub - SSD MobileNet V2 Open Images V4](https://tfhub.dev)

## Technologies Used

- TensorFlow
- Keras
- TensorFlow Hub
- NumPy
- Matplotlib
- Gradient Descent optimizers (SGD, Adam, RMSprop, etc.)

## Objective

To detect and localize dogs in images using a pre-trained object detection model. The project involves training on a custom dog image dataset and experimenting with different optimizers.

