# COMP551_A2 - ML Project 2: Investigating Model Complexity, Bias-Variance Trade-off, and Regularization Techniques in Linear Regression

Team Members: Diana Covaci, Nicholas Milin, Viktor Allais

This project investigates the behavior of Linear Regression under varying levels of model complexity, explores the bias-variance trade-off, and analyzes the impact of L1, L2, and Elastic Net regularization techniques. All models were implemented entirely from scratch in Python using NumPy for numerical computations and Matplotlib for visualizations. The goal of this project was to develop a deeper understanding of how linear regression behaves under different levels of complexity and regularization. We generated synthetic data to run these experiments. 

---

## Repository Structure 

```
COMP551_A2/
├── code.ipynb        # Main script with experiments (run in VS Code)
├── writeup.pdf       # Project report
└── README.md         # Project documentation
```
--- 


## Features
- Synthetic data generation with Gaussian noise
- Linear regression model implementation
- Non-linear basis expansion with Gaussian basis functions
- L1, L2, and Elastic Net regularization implementations
- Cross-validation for regularization strengths
- Bias-variance decomposition through repeated randomized trials
- Visualization of experiments

### Prerequisites

- Python 3.8+  
- pip (Python package manager)  
- VS Code or any Python IDE/terminal  

## Installation & Setup

1. Clone this repository: 

   ```bash
   git clone https://github.com/dianacovacii/COMP551_A2.git
   cd COMP551_A2
   ```

2. Open the notebook and run the cells.  

## Usage

1. Run the cells in order, it will:

   * Generate synthetic data with controlled Gaussian noise
   * Construct non-linear models using Gaussian basis functions
   * Experiment with different types of regularization
   * Perform k-fold cross-validation to tune 
   * Plot model fits, loss contours, and bias-variance visualizations

---

## Report

The accompanying report (writeup.pdf) provides a comprehensize analysis of our findings, including: 
   * Derivation and implementation of linear regression with non-linear basis functions
   * Exploration of model complexity and the bias-variance trade-off
   * Impact of L1, L2, and Elastic Net regularization on model performance
   * Cross-validation results for optimal hyperparameter selection 
   * Comparison of analytical and gradient descent optimization methods
   * Discussion of convergence behavior and generalization performance

--- 

## Acknowledgments

This project was completed as part of the COMP551 (Applied Machine Learning) course at McGill University in Fall 2025.
