# Deep Learning Perceptron Task

This project implements a single-layer perceptron algorithm for classification and demonstrates its performance on two different datasets with varying levels of separability.

## Setup

### Prerequisites
- Python 3.10+
- Virtual environment (recommended)

### Installation

1. **Clone or navigate to the project directory:**
   ```bash
   cd deep-learning-perceptron-task
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## What the Notebook Does

1. **Implements a Perceptron class** with configurable learning rate, max epochs, and shuffling
2. **Exercise 1**: Tests on linearly separable data (2D Gaussian distributions with clear separation)
3. **Exercise 2**: Tests on overlapping data (2D Gaussian distributions with significant overlap)
4. **Generates visualizations**:
   - Data scatter plots
   - Decision boundary plots
   - Accuracy over epochs
   - Misclassified points highlighting

## Expected Results

- **Exercise 1**: Should achieve ~100% accuracy (linearly separable data)
- **Exercise 2**: Will show lower accuracy (~60-70%) due to data overlap, demonstrating perceptron limitations

## Dependencies

Key packages used:
- `numpy`: Numerical computations
- `matplotlib`: Plotting and visualization
- `jupyter`: Interactive notebook environment
