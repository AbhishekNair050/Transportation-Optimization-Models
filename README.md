# Transportation-Optimization-Models

This repository contains Python scripts implementing various models for solving transportation problems for the review that we conducted on [Analyzing multimodal transportation problem and its application to artificial intelligence](https://link.springer.com/article/10.1007/s00521-019-04393-5), which includes linear programming and neural network approaches. These models are designed for solving transportation problems with different constraints and objectives.

## Models Implemented

### Model 1: Linear Programming for Transportation Problem
- This model utilizes the `scipy.optimize.linprog` function to solve a basic transportation problem.
- It provides a function `solve_transportation_problem` that takes costs, supplies, and demands as input and returns the optimal transportation plan.

### Model 2: Linear Programming for Multimodal Transportation Problem
- This model extends Model 1 to handle multimodal transportation problems.
- It provides a function `solve_multimodal_transportation_problem` that takes cost matrices, availabilities, demands, and storages as input and returns the optimal transportation plan.

### Model 3: Neural Network Approach using PyTorch
- This model implements a Multi-Layer Perceptron (MLP) using PyTorch to solve a specific transportation problem.
- It defines the MLP architecture and a custom loss function tailored to the problem.
- It includes a training loop to optimize the MLP parameters using gradient descent.

### Model 4: Generalized Neural Network Approach using TensorFlow
- This model implements a generalized MLP using TensorFlow to solve transportation problems.
- It defines a TensorFlow Keras model class for the MLP and a custom loss function.
- It includes a training loop to optimize the model parameters using gradient descent.

## Usage
- Each model script can be executed independently.
- Ensure that required dependencies such as NumPy, SciPy, PyTorch, and TensorFlow are installed.
- Modify input data and parameters as needed for your specific transportation problem.

## Citation
If you use any of these models in your research work, please cite the original research paper:

Maity, G., Roy, S.K. & Verdegay, J.L. Analyzing multimodal transportation problem and its application to artificial intelligence. *Neural Comput & Applic* 32, 2243–2256 (2020). [https://doi.org/10.1007/s00521-019-04393-5](https://doi.org/10.1007/s00521-019-04393-5)

