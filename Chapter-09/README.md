# Chapter-09: Transformations and Computation

**Source Textbook Reference:** `08.Maths-for-IT/chapters/10-transformations-and-computation.tex`  
**Course:** ITSU1012 / ITSU1012R — Maths for IT, ML, AI and LLMs

Model 2D and 3D linear transformations with matrices, compose homogeneous transforms for graphics pipelines, and verify `np.linalg.solve` solutions via residual norms.

## Notebooks

| Notebook | Focus & IT Application | Mathematical Foundations | Est. Time | Colab |
| :--- | :--- | :--- | :--- | :--- |
| [`01-2d-rotation-and-scaling.ipynb`](01-2d-rotation-and-scaling.ipynb) | 2D rotation, scaling, shear, and transformation composition order | $R(\theta)$, $\operatorname{diag}(s_x, s_y)$, $RS\mathbf{v} \neq SR\mathbf{v}$ | 15–20 min | [Colab](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-09/01-2d-rotation-and-scaling.ipynb) |
| [`02-3d-homogeneous-transforms.ipynb`](02-3d-homogeneous-transforms.ipynb) | 3D scaling, $z$-rotation, and translation in $4\times 4$ homogeneous coordinates | $4\times 4$ homogeneous matrices, $(x,y,z,1)^T$ | 15–20 min | [Colab](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-09/02-3d-homogeneous-transforms.ipynb) |
| [`03-linear-system-residuals.ipynb`](03-linear-system-residuals.ipynb) | Residual checks $\lVert A\mathbf{x} - \mathbf{b}\rVert_2$ and condition numbers | Residual $\mathbf{r}=A\mathbf{x}-\mathbf{b}$, $\kappa(A)$ | 15–20 min | [Colab](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-09/03-linear-system-residuals.ipynb) |

## How to Complete

1. Open a notebook in Google Colab (using the badge above) or in local JupyterLab / VS Code.
2. Read the mathematical context and worked-example references.
3. Replace each `# TODO: ...` and `raise NotImplementedError(...)` with your implementation.
4. Run all cells top-to-bottom and verify that every `assert` passes.
