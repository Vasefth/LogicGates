# LogicGates

# Perceptron Logic Gates Simulation

## Overview

This project demonstrates the application of perceptrons, a type of artificial neuron, to simulate basic logic gates (AND, OR, XOR) that are fundamental to digital circuits and computing. Perceptrons are trained to model the behavior of these logic gates using a simple dataset representing the gate's truth table. The project not only explores the capability of perceptrons to learn linearly separable problems (AND, OR gates) but also illustrates their limitation with linearly inseparable problems (XOR gate).

## Project Structure

- **Perceptron Training:** Utilizes the `Perceptron` class from `sklearn.linear_model` to train a perceptron model on the truth tables of AND, OR, and XOR gates.
- **Visualization:** Plots data points on a scatter plot and visualizes the decision boundary learned by the perceptron. Additionally, a heatmap is generated to show the decision function's output across a grid of points.

## Dependencies

- Python 3.x
- NumPy
- Matplotlib
- Scikit-learn

## Installation

Ensure Python 3.x is installed on your system. You can then install the required Python packages using pip:

```bash
pip install numpy matplotlib scikit-learn
```

## Usage

Run the script to train perceptron models on the truth tables of logic gates. The script will output the accuracy of the models and display visualizations for the decision boundaries:

```bash
python perceptron_logic_gates.py
```

## Key Concepts

- **Logic Gates:** Basic computing building blocks that perform logical operations on two binary inputs to produce a single binary output.
- **Perceptron:** A simple linear classifier used for binary classification tasks.
- **Linear Separability:** A dataset is linearly separable if it can be perfectly classified into two categories by a linear boundary.

## Results and Discussion

- The perceptron successfully learns to model AND and OR gates, which are linearly separable problems.
- The XOR gate, being a linearly inseparable problem, cannot be modeled with a single perceptron, highlighting a fundamental limitation of perceptrons in representing complex logical functions.

## Further Exploration

- Explore how multi-layer perceptrons (MLPs) or neural networks can overcome the limitations observed with the XOR gate by using layers of perceptrons to capture non-linear decision boundaries.
- Experiment with different learning rates and iterations for the perceptron training to observe how they affect the convergence and accuracy of the models.

## Contributing

Contributions, bug reports, and feature requests are welcome! Feel free to fork the repository and submit pull requests with your enhancements.
