# Quickstart — Chapter-09: Transformations and Computation

## Option 1: Google Colab (Recommended)
Click any **Open in Colab** badge in [`README.md`](README.md) or at the top of a `.ipynb` file. No local installation is required; only Python 3.10+ standard library and `numpy` are used.

## Option 2: Local Jupyter / VS Code
```bash
cd 09.Maths-for-IT-Notebooks/Chapter-09
jupyter lab
```

## Notebooks in This Chapter
- `01-2d-rotation-and-scaling.ipynb` — 2D rotation, scaling, shear, and transformation composition order
- `02-3d-homogeneous-transforms.ipynb` — 3D scaling, $z$-rotation, and translation in $4\times 4$ homogeneous coordinates
- `03-linear-system-residuals.ipynb` — Residual checks $\lVert A\mathbf{x} - \mathbf{b}\rVert_2$ and condition numbers

## Self-Check Workflow
Each notebook ends with a self-check cell containing `assert` statements aligned with the textbook worked examples. Before you implement the `# TODO` blocks, running the notebook raises `NotImplementedError`. Once complete, all cells should execute in under 5 seconds with zero errors.
