# Image Style Transfer with AdaIN

This project implements a neural network for real-time style transfer using **Adaptive Instance Normalization (AdaIN)**. The model can dynamically transfer the artistic style from one image onto another without being fixed to a singular trained style, allowing for diverse style applications. The work is inspired by the research paper [_Arbitrary Style Transfer in Real-Time with Adaptive Instance Normalization_](https://arxiv.org/abs/1703.06868).

## Project Overview
- **Objective**: Build and train a model capable of transferring the style of one image onto another, using an adaptive and flexible approach.
- **Technologies Used**:
  - Python
  - TensorFlow/Keras
  - Pre-trained VGG16 model
- **Data Source**: Kaggle image dataset
- **Key Components**:
  - **Exploratory Data Analysis (EDA)**
  - **Principal Component Analysis (PCA)**
  - **Transfer Learning with VGG16**
  - **AdaIN Layer Implementation**

## Features
- Real-time style transfer leveraging AdaIN for flexible and adaptive styling.
- Combination of transfer learning and neural network design to achieve fast and efficient training.
- EDA and PCA for data preprocessing and visualization.

## Model Architecture
The project utilizes a pre-trained VGG16 model as a feature extractor, with an additional AdaIN layer that enables the blending of content and style features.

### Adaptive Instance Normalization (AdaIN)
AdaIN aligns the channel-wise mean and variance of the content image's features to match those of the style image's features. This adaptation is done through a simple, computationally efficient process, enabling real-time performance.

## Getting Started

### Prerequisites
- Python 3.x
- TensorFlow/Keras
- NumPy, Pandas, Matplotlib
- Kaggle API for dataset access

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/SethWM96/image-style-transfer-AdaptiveInstanceNormalization.git
