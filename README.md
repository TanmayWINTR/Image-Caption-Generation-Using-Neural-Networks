# Image-Caption-Generation-Using-Neural-Networks

## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Notebook File](#notebook-file)
- [Getting Started](#getting-started)
- [Features](#features)
- [Evaluation Metrics](#evaluation-metrics)
- [Usage](#usage)


## Introduction
Welcome to my GitHub repository! This project is focused on the task of generating descriptive captions for images. The model leverages Convolutional Neural Networks (CNNs), specifically using a ResNet-50 architecture, to extract salient features from images. These features are then used to generate corresponding captions that aim to describe the content of the images accurately. The project offers a comprehensive solution for the automatic generation of image captions, incorporating feature extraction, data preprocessing, model training, and evaluation.

## Technologies
- Python 3.x
- PyTorch
- Google Colab
- NLTK
- Matplotlib
- Pandas

## Notebook File
This repository features a Google Colab Notebook named `Image_Caption_Generation_Using_Neural_Networks.ipynb`, which you can use to train and evaluate the model interactively. 

## Getting Started
1. Clone the repository.
    ```bash
    git clone https://github.com/TanmayWINTR/ImageCaptionGeneration.git
    ```
2. Open the Google Colab Notebook:
    ```bash
    Image_Caption_Generation_Using_Neural_Networks.ipynb
    ```

## Features
- **Encoder-Decoder Model**: Utilises ResNet-50 for image encoding and a custom RNN for text decoding.
- **Data Preprocessing**: Offers text cleaning and vocabulary building.
- **Batch Training**: Uses mini-batch gradient descent for efficient training.
- **Model Checkpointing**: Allows saving and restoring of model states.

## Evaluation Metrics
- **BLEU Score**: Measures the similarity between the generated captions and the reference captions based on n-gram precision.
- **Cosine Similarity**: Evaluates the semantic similarity between the generated and reference captions.

## Usage
1. Navigate to the Google Colab Notebook in the repository.
2. Follow the instructions within the notebook to train and evaluate the model.



---

For more information, please refer to the Google Colab Notebook `Image_Caption_Generation_Using_Neural_Networks.ipynb` included in this repository. Feel free to raise issues or make pull requests. Thank you for visiting!
