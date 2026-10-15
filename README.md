# Next Word Predictor using LSTM

This project builds and trains a deep learning model that predicts the next word in a text sequence. It uses a collection of FAQ text as its training corpus and applies natural language processing techniques to prepare the text, learn word-sequence patterns, and generate continuations from a prompt.

The project demonstrates an end-to-end NLP workflow, from text preprocessing and sequence generation to model training and prediction.

## Project workflow

1. **Prepare the text** — load the FAQ content and tokenize it into words.
2. **Create training sequences** — turn the text into progressively longer sequences, then pad them to a consistent length.
3. **Build the model** — use an embedding layer to represent words, an LSTM layer to learn sequence patterns, and a softmax output layer to predict the next word.
4. **Train the model** — optimize the network on the prepared sequences.
5. **Generate predictions** — provide a starting phrase and let the model predict the next word. Repeat predictions to generate a longer continuation.

## Technologies

- **Python 3** — project language
- **Jupyter Notebook** — interactive development and execution environment
- **TensorFlow / Keras** — neural network construction and training
- **LSTM** — sequence-learning layer for modeling word order and context
- **NumPy** — numerical and array operations
- **Keras text preprocessing** — tokenization, sequence padding, and categorical encoding

The notebook also imports **pandas**, although it is not required for the model workflow.
