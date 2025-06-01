# Next Word Prediction using Deep Learning

## Overview
This project implements a deep learning-based *Next Word Prediction* model using **Long Short-Term Memory (LSTM)** networks. The model is trained on text from Franz Kafka’s *Metamorphosis* sourced from **Project Gutenberg**, enabling it to predict probable next words based on sequences from the book.

## Features
- Uses an LSTM-based Recurrent Neural Network (RNN) for sequence prediction.
- Trained on *Metamorphosis* for language modeling.
- Tokenization and preprocessing of Kafka's text data.
- Implements word embeddings for efficient representation.
- Generates probable next-word suggestions for given input sequences.

## Installation
To set up the project, install the dependencies:
```bash
pip install tensorflow
```

## Dataset
The model is trained on *Metamorphosis*, a literary text from Project Gutenberg. The book provides rich vocabulary and sentence structures, making it ideal for next-word predictions.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
