# Transfer Learning with PyTorch
This repository contains a transfer learning project using PyTorch. The goal is to fine-tune a pre-trained convolutional neural network (CNN) model to classify images from a specific dataset.


## Project Overview

Transfer learning is a powerful technique where a pre-trained model is used as the starting point for a new task. This project demonstrates how to fine-tune a pre-trained ResNet-18 model and VGG-16 model on a custom dataset for image classification. By leveraging the knowledge from a model pre-trained on a large dataset (such as ImageNet), we can achieve high accuracy even with a smaller dataset.


## Dataset

The dataset used in this project is sourced from Kaggle. It contains images for the purpose of card classification. Below are the details and instructions for accessing the dataset.

### Source

The dataset is available on Kaggle at the following link: [Cards Image Dataset-Classification](https://www.kaggle.com/gpiosenka/cards-image-datasetclassification)

### Description

- **Number of Classes**: 53 (52 playing cards plus a joker)
- **Number of Images**: 14,630 images
- **Image Size**: Various sizes, typically around 300x400 pixels
- **File Format**: JPEG/PNG

### Downloading the Dataset

#### Kaggle API

Use the Kaggle API to download the dataset directly. First, ensure you have the Kaggle API installed and configured. Follow the instructions here: [Kaggle API](https://www.kaggle.com/docs/api).

```bash
pip install kaggle
kaggle datasets download -d gpiosenka/cards-image-datasetclassification 
```
### Acknowledgements

Acknowledge the source of the dataset:

This dataset is provided by [gpiosenka](https://www.kaggle.com/gpiosenka) on Kaggle. Full credit goes to the original authors and contributors.

## Model

Describe the model and the transfer learning approach:

- The pre-trained model used (e.g., ResNet-18 , VGG-16)
- The modifications made (e.g., replacing the final fully connected layer)




