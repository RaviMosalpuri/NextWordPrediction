# Next Word Prediction using Deep Learning

## Overview
This project implements a deep learning-based *Next Word Prediction* model using **Long Short-Term Memory (LSTM)** networks. The model is trained on text from Franz Kafka’s *Metamorphosis* and *The Trial*, sourced from **[Project Gutenberg](https://www.gutenberg.org/)**, enabling it to predict probable next words based on sequences from the book.

## Features
- Uses an LSTM-based Recurrent Neural Network (RNN) for sequence prediction.
- Trained on *Metamorphosis* and *The Trial* for language modeling.
- Tokenization and preprocessing of Kafka's text data.
- Implements word embeddings for efficient representation.
- Generates probable next-word suggestions for given input sequences.

## Installation
To set up the project, install the dependencies:
```bash
pip install tensorflow numpy
```

## Dataset
The model is trained on *Metamorphosis* and *The Trial* from Project Gutenberg. The books provides rich vocabulary and sentence structures, making it ideal for next-word predictions.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
