# Seq2Seq Translation Model

This project implements a sequence-to-sequence (seq2seq) model for translating text from English to French using Keras and TensorFlow. The model is trained on a dataset of English-French sentence pairs.

## Overview

- **Dataset**: English-French sentence pairs from `fra-eng/fra.txt`.
- **Preprocessing**: Data is vectorized into one-hot encoded numpy arrays.
- **Model Architecture**: 
  - Encoder LSTM processes the input English sentences.
  - Decoder LSTM generates the output French sentences.
  - Dense layers with softmax activation predict the next character.
- **Training**: The model is trained using the teacher forcing technique.

## Requirements

- Python 3.x
- TensorFlow
- NumPy

Install the required packages using pip:

```bash
pip install tensorflow numpy
