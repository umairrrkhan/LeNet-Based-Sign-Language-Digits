# LeNet-Based Sign Language Digits Recognition

Welcome to the **LeNet-Based Sign Language Digits Recognition** project! This project focuses on recognizing sign language digits using the LeNet-5 convolutional neural network architecture. The goal is to accurately classify hand gestures representing digits from 0 to 9 in sign language.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

Sign language is an essential mode of communication for people with hearing impairments. This project aims to bridge the communication gap by recognizing hand gestures corresponding to digits in sign language using deep learning techniques. We leverage the LeNet-5 architecture, a classic convolutional neural network, to achieve accurate digit classification.

## Installation

To set up and run the project locally, follow these steps:

1. Clone the repository:
   
   ```bash
   git clone https://github.com/umairrrkhan/LeNet-Based-Sign-Language-Digits.git
   cd LeNet-Based-Sign-Language-Digits
   ```
2. Install the required dependencies:

```bash
pip install numpy matplotlib seaborn tensorflow scikit-learn
```

## Usage

Once you've installed the necessary dependencies, you can use the provided scripts to train and evaluate the model.


## Dataset

The dataset used for this project is sourced from the Kaggle website. It contains images of hand gestures representing sign language digits. The dataset is divided into training and testing sets, allowing us to train and assess the model's performance effectively. [Visit dataset](https://www.kaggle.com/datasets/ardamavi/sign-language-digits-dataset)

## Model Architecture

The LeNet-5 architecture consists of several convolutional and pooling layers, followed by fully connected layers. It's a pioneering design for image classification tasks and serves as the foundation for many modern convolutional neural networks.

## Training

During training, the dataset is preprocessed, and the LeNet-5 model is trained using an appropriate optimization algorithm (e.g., Adam optimizer) and loss function (e.g., categorical cross-entropy). The model's weights are adjusted iteratively to minimize the loss, resulting in improved accuracy over epochs.

## Evaluation

The model's performance is evaluated using a separate test dataset. The accuracy metric is commonly used to assess the model's ability to correctly classify sign language digits.

## Results

After training and evaluation, the model achieves an accuracy of around XX% on the test dataset. This demonstrates the effectiveness of the LeNet-5 architecture in recognizing sign language digits.

## Contributing

Contributions to this project are welcome! If you'd like to contribute, please follow the standard GitHub workflow: fork the repository, make your changes, and submit a pull request.
