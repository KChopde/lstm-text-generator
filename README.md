
# LSTM Text Generator using PyTorch

This project implements a word-level LSTM-based text generator using **PyTorch**. It trains on a custom input text and learns to predict the next word in a sequence. The generated model can then produce poetic or narrative-like outputs based on a seed phrase.

# Features

- Tokenizes and preprocesses raw input text
- Creates sequences of fixed length to train on next-word prediction
- Uses an LSTM model with:
  - Word embeddings
  - 2 LSTM layers
  - Dropout regularization
- Trains using 'CrossEntropyLoss' and 'Adam' optimizer
- Generates new text from any given seed
- Visualizes training loss per epoch using 'matplotlib'


# Installation

Run the following in Google Colab or your local Python environment:

```bash
!pip install torch matplotlib numpy
