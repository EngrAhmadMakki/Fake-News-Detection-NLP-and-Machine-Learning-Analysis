# Fake News Detection using NLP and Machine Learning

This project focuses on detecting fake news using Natural Language Processing (NLP) techniques and Machine Learning models. The goal is to build a model that can accurately classify news articles as either real or fake.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

Fake news has become a significant issue in today's digital world. This project aims to address this problem by developing a model capable of identifying fake news articles. The model utilizes a combination of NLP techniques and machine learning algorithms to achieve this task.

## Dataset

The dataset contains news articles labeled as either real or fake. It has been preprocessed to clean and standardize the text, making it suitable for model training and evaluation.

## Model Architecture

The neural network model consists of the following layers:
- **Input Layer**: Accepts the preprocessed text features.
- **Hidden Layer**: 128 neurons with ReLU activation function.
- **Output Layer**: 1 neuron with sigmoid activation function for binary classification.

The model is compiled with the Adam optimizer and binary cross-entropy loss function, using accuracy as the metric for evaluation.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
git clone https://github.com/EngrAhmadMakki/Fake-News-Detection-NLP-and-Machine-Learning-Analysis.git
cd Fake-News-Detection-NLP-and-Machine-Learning-Analysis


2. Create a virtual environment and activate it:


3. Install the required packages:


## Usage

To run the model, use the Jupyter Notebook `FakeNewsPrediction.ipynb`. You can start Jupyter Notebook by running:



Follow the steps in the notebook to preprocess the data, train the model, and evaluate its performance.

## Results

The model achieved a training accuracy of 100% and a testing accuracy of approximately 99%. This indicates the model's high effectiveness in differentiating between real and fake news articles.

## Contributing

If you'd like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

We would like to thank the authors of the datasets and tools used in this project, as well as the contributors to open-source libraries that made this work possible.
