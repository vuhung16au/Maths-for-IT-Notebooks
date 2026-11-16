# Chapter 15: Derivatives, Chain Rule and Numerical Stability

**Book Reference:** Chapter 15 (`chapters/derivatives-chain-rule-stability.tex`)

## Learning Goals
- Approximate derivatives numerically using central finite differences and verify the chain rule.
- Prevent floating-point overflow in `softmax` and `logsumexp` via the max-shift trick.
- Approximate definite integrals and continuous probability densities using Riemann sums.

## Notebooks
| Notebook | Topic | Colab |
| :--- | :--- | :--- |
| `01-numerical-differentiation-chain-rule.ipynb` | Finite differences & chain rule for $\sigma(2x+1)$ | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-15/01-numerical-differentiation-chain-rule.ipynb) |
| `02-stable-softmax-logsumexp.ipynb` | Naive vs max-shifted `softmax` & `logsumexp` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-15/02-stable-softmax-logsumexp.ipynb) |
| `03-riemann-sum-integration.ipynb` | Left, right, and midpoint Riemann sums | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-15/03-riemann-sum-integration.ipynb) |
