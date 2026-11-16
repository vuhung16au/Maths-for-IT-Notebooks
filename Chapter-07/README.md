# Chapter-07: Vectors and Coordinates

**Source Textbook Reference:** `08.Maths-for-IT/chapters/08-vectors-and-coordinates.tex`  
**Course:** ITSU1012 / ITSU1012R — Maths for IT, ML, AI and LLMs

Explore 2D, 3D, and $n$-dimensional vectors, displacement, `atan2` quadrant angles, dot products, orthogonality, and toy word embeddings.

## Notebooks

| Notebook | Focus & IT Application | Mathematical Foundations | Est. Time | Colab |
| :--- | :--- | :--- | :--- | :--- |
| [`01-vector-operations-and-atan2.ipynb`](01-vector-operations-and-atan2.ipynb) | Displacement, magnitude, unit vectors, and quadrant-safe `atan2` | Euclidean norm $\lVert\mathbf{v}\rVert$, $\operatorname{atan2}(v_y, v_x)$ | 15–20 min | [Colab](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-07/01-vector-operations-and-atan2.ipynb) |
| [`02-dot-product-and-orthogonality.ipynb`](02-dot-product-and-orthogonality.ipynb) | Dot product from scratch, orthogonality, and vector angles | $\mathbf{u}\cdot\mathbf{v} = \sum u_i v_i$, $\cos\theta$ | 15–20 min | [Colab](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-07/02-dot-product-and-orthogonality.ipynb) |
| [`03-toy-word-embeddings.ipynb`](03-toy-word-embeddings.ipynb) | 4D token embeddings and semantic analogy arithmetic | Cosine similarity, vector offset $\mathbf{c} + (\mathbf{b} - \mathbf{a})$ | 15–20 min | [Colab](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-07/03-toy-word-embeddings.ipynb) |

## How to Complete

1. Open a notebook in Google Colab (using the badge above) or in local JupyterLab / VS Code.
2. Read the mathematical context and worked-example references.
3. Replace each `# TODO: ...` and `raise NotImplementedError(...)` with your implementation.
4. Run all cells top-to-bottom and verify that every `assert` passes.
