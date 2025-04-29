# Iris Dataset Classification using PyTorch

This project demonstrates a simple neural network built with **PyTorch** to classify flowers from the famous **Iris dataset** into three species: *Setosa*, *Versicolor*, and *Virginica*.

## Dataset

The Iris dataset contains:
- 150 samples
- 4 features per sample:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
- 3 target classes (species)

It is a classic dataset widely used for beginner-level for machine learning tasks.

## Project Structure

- `main.ipynb`: Jupyter notebook containing the full code for loading data, building the model, training, and evaluating it.

## Steps

1. Load the Iris dataset using `pandas`.
2. Convert the data into a PyTorch-friendly format (Tensors).
3. Build a simple feedforward neural network with:
   - Input layer (4 features)
   - Hidden layers
   - Output layer (3 classes)
4. Train the model using Cross-Entropy Loss and an optimizer SGD.


## Requirements

- Python 3.x
- PyTorch
- pandas


Install dependencies:
```bash
pip install torch torchvision pandas 
