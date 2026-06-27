# Polynomial Regression using Convex Optimization

A machine learning project that implements **Polynomial Regression** using **Convex Optimization (CVXPY)** and compares it with multiple iterative optimization algorithms, including **Gradient Descent (GD)**, **Accelerated Gradient Descent (AGD)**, and **Stochastic Gradient Descent (SGD)**. The project also explores the effects of **LASSO (L1) Regularization** and **Gaussian Noise** on model performance and optimization.

---

## Features

- Polynomial Feature Mapping for nonlinear regression
- Convex Optimization using CVXPY
- Gradient Descent implementation from scratch
- Accelerated Gradient Descent (Nesterov)
- Stochastic Gradient Descent (SGD)
- LASSO (L1) Regularization
- Gaussian Noise Robustness Analysis
- Residual Analysis
- Convergence Visualization
- Cost Function Comparison

---

## Algorithms Implemented

### Convex Optimization
Uses **CVXPY** to compute the optimal least-squares solution for polynomial regression.

### Gradient Descent
Implements standard batch Gradient Descent for minimizing the regression objective.

### Accelerated Gradient Descent
Implements Nesterov's Accelerated Gradient Descent to improve convergence speed.

### Stochastic Gradient Descent
Uses randomly sampled data points for efficient optimization on larger datasets.

### LASSO Regularization
Introduces an L1 penalty to encourage sparse model coefficients and study model complexity.

### Gaussian Noise Analysis
Adds Gaussian noise to the target variable to evaluate model robustness under noisy conditions.

---

## Technologies Used

- Python
- NumPy
- Matplotlib
- CVXPY
- Jupyter Notebook

---

## Repository Structure

```
Polynomial-Regression-Optimization/
│
├── PolynomialRegression.ipynb
├── dataset.csv
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Results

The project compares:

- Convex Optimization vs Gradient-based Optimization
- GD vs AGD vs SGD
- Effect of LASSO Regularization
- Effect of Gaussian Noise
- Cost Function Convergence
- Residual Distribution

The convergence plots demonstrate the optimization behaviour of different algorithms, while residual analysis provides insight into model accuracy and robustness.

---

## How to Run

Clone the repository

```bash
git clone https://github.com/rishi1205/polynomial-regression.git
```

Navigate to the project directory

```bash
cd polynomial-regression
```

Install the required dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook PolynomialRegression.ipynb
```

## Learning Outcomes

This project demonstrates practical implementation of:

- Convex Optimization
- Numerical Optimization Algorithms
- Polynomial Regression
- Regularization Techniques
- Model Robustness Analysis
- Scientific Computing in Python
- Data Visualization

---

## Author

**Rishi Trivedi**

GitHub: https://github.com/rishi1205
