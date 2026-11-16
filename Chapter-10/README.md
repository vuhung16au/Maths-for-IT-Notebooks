# Chapter-10: More Linear Algebra

**Source Textbook Reference:** `08.Maths-for-IT/chapters/20-more-linear-algebra.tex`  
**Course:** ITSU1012 / ITSU1012R — Maths for IT, ML, AI and LLMs

Implement cosine similarity ranking, orthogonal projections, Gram–Schmidt orthonormalisation, rank-based system classification, and least-squares line fitting.

## Notebooks

| Notebook | Focus & IT Application | Mathematical Foundations | Est. Time | Colab |
| :--- | :--- | :--- | :--- | :--- |
| [`01-cosine-similarity-and-ranking.ipynb`](01-cosine-similarity-and-ranking.ipynb) | Cosine similarity and ranking candidate embeddings against a query | $\cos\theta = \frac{\mathbf{u}\cdot\mathbf{v}}{\lVert\mathbf{u}\rVert\lVert\mathbf{v}\rVert}$ | 15–20 min | [Colab](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-10/01-cosine-similarity-and-ranking.ipynb) |
| [`02-vector-projection-gram-schmidt.ipynb`](02-vector-projection-gram-schmidt.ipynb) | Orthogonal projection and Gram–Schmidt orthonormalisation | $\operatorname{proj}_{\mathbf{u}}\mathbf{v}$, $Q^T Q = I$ | 20–25 min | [Colab](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-10/02-vector-projection-gram-schmidt.ipynb) |
| [`03-linear-independence-and-rank.ipynb`](03-linear-independence-and-rank.ipynb) | Linear independence, collinearity detection, and rank classification | $\operatorname{rank}(A)$ vs $\operatorname{rank}([A\mid\mathbf{b}])$ | 15–20 min | [Colab](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-10/03-linear-independence-and-rank.ipynb) |
| [`04-least-squares-line-fitting.ipynb`](04-least-squares-line-fitting.ipynb) | Least-squares line fitting via normal equations and `np.linalg.lstsq` | $A^T A \mathbf{w} = A^T \mathbf{y}$, $\operatorname{RSS}$, $A^T \mathbf{r} = \mathbf{0}$ | 20–25 min | [Colab](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-10/04-least-squares-line-fitting.ipynb) |

## How to Complete

1. Open a notebook in Google Colab (using the badge above) or in local JupyterLab / VS Code.
2. Read the mathematical context and worked-example references.
3. Replace each `# TODO: ...` and `raise NotImplementedError(...)` with your implementation.
4. Run all cells top-to-bottom and verify that every `assert` passes.
