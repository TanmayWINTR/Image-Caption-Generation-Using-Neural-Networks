# Image-Caption-Generation-Using-Neural-Networks

## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Notebook File](#notebook-file)
- [Getting Started](#getting-started)
- [Features](#features)
- [Evaluation Metrics](#evaluation-metrics)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Welcome to my GitHub repository! This project is focused on the task of generating descriptive captions for images, implemented using a combination of Convolutional Neural Networks (CNNs) for feature extraction and Recurrent Neural Networks (RNNs) for caption generation. 

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

## Contributing
Contributions to this project are welcomed. Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.

## License
This project is licensed under the MIT License. Please see the [LICENSE.md](LICENSE.md) file for details.

---

For more information, please refer to the Google Colab Notebook `Image_Caption_Generation_Using_Neural_Networks.ipynb` included in this repository. Feel free to raise issues or make pull requests. Thank you for visiting!
