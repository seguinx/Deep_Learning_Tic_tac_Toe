# Deep Learning Tic-Tac-Toe AI

This project is a deep learning-based Tic-Tac-Toe AI built with TensorFlow and Keras.

The project includes three main steps:

1. Training a first model on the provided dataset.
2. Generating new training data by having the model play against itself.
3. Training a second model on the generated data and comparing it with the original model.

## Project Goal

The goal is to create a neural network that can predict the best next move in a Tic-Tac-Toe game.

## How It Works

- The game board is represented as a vector of 9 values.
- `0` means an empty cell.
- `1` means `X`.
- `-1` means `O`.

The problem is treated as a multi-class classification task, where the model predicts the best move among the 9 possible positions.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Jupyter Notebook

## Files

- `winner_moves.csv` — dataset generated from self-play
- Jupyter Notebook — complete project implementation

## Author

UA 3 project.
