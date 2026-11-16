# Chapter-08: Matrices and Linear Systems

**Source Textbook Reference:** `08.Maths-for-IT/chapters/09-matrices-and-linear-systems.tex`  
**Course:** ITSU1012 / ITSU1012R — Maths for IT, ML, AI and LLMs

Implement matrix multiplication from scratch, verify non-commutativity, compute determinants and inverses, and solve linear systems via `np.linalg.solve` and Gaussian elimination.

## Notebooks

| Notebook | Focus & IT Application | Mathematical Foundations | Est. Time | Colab |
| :--- | :--- | :--- | :--- | :--- |
| [`01-matrix-multiplication-noncommutativity.ipynb`](01-matrix-multiplication-noncommutativity.ipynb) | Matrix multiplication from scratch, non-commutativity, and batch neural layers | $C_{ij} = \sum_k A_{ik}B_{kj}$, $AB \neq BA$, $XW^T + \mathbf{b}$ | 15–20 min | [Colab](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-08/01-matrix-multiplication-noncommutativity.ipynb) |
| [`02-solving-linear-systems.ipynb`](02-solving-linear-systems.ipynb) | $2\times 2$ determinants/inverses and `np.linalg.solve` on $2\times 2$ and $3\times 3$ systems | $\det(A)=ad-bc$, $A^{-1}$, $A\mathbf{x}=\mathbf{b}$ | 15–20 min | [Colab](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-08/02-solving-linear-systems.ipynb) |
| [`03-gaussian-elimination-from-scratch.ipynb`](03-gaussian-elimination-from-scratch.ipynb) | Row reduction with partial pivoting and back-substitution | Augmented matrix $[A \mid \mathbf{b}]$, upper-triangular reduction | 20–25 min | [Colab](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-08/03-gaussian-elimination-from-scratch.ipynb) |

## How to Complete

1. Open a notebook in Google Colab (using the badge above) or in local JupyterLab / VS Code.
2. Read the mathematical context and worked-example references.
3. Replace each `# TODO: ...` and `raise NotImplementedError(...)` with your implementation.
4. Run all cells top-to-bottom and verify that every `assert` passes.
