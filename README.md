# Next Word Predictor using LSTM

This project is a small natural language processing demo that predicts the next word in a text sequence.

The notebook uses a collection of frequently asked questions as its sample text. It converts the text into number sequences, trains an LSTM neural network to learn patterns in those sequences, and then uses the trained model to suggest likely next words.

## How it works

1. The notebook prepares the FAQ text and tokenizes its words.
2. It creates training sequences from the text and pads them to a consistent length.
3. It trains a neural network with an embedding layer, an LSTM layer, and a softmax output layer.
4. Given a starting phrase, the model predicts a next word. The notebook can repeat this process to generate a longer continuation.

This is an educational project demonstrating a basic next-word prediction workflow. Its predictions are based only on the sample text in the notebook, so it is not a general-purpose writing or language model.

## Technologies

- **Python 3** — programming language
- **Jupyter Notebook** — interactive environment for running the project
- **TensorFlow / Keras** — model building and training
- **LSTM** — recurrent neural network layer used to learn sequences
- **NumPy** — array and numerical operations
- **Keras text preprocessing** — tokenization, sequence padding, and categorical encoding

The notebook also imports **pandas**, though it is not needed for the model workflow.
