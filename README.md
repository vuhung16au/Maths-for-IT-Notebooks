# Maths for IT, ML, AI and LLMs — Interactive Python Notebooks

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Course: ITSU1012](https://img.shields.io/badge/Course-ITSU1012%20%2F%20ITSU1012R-orange.svg)](https://github.com/vuhung16au/VIT-Notes)

Welcome to the interactive Python exercise repository for **"Maths for IT, ML, AI and LLMs"** (Course code: **ITSU1012 / ITSU1012R**).

This platform bridges theoretical mathematical principles with computational practice. Rather than treating mathematics as dry abstraction or Python as mere syntax, each computational lab translates rigorous mathematical theorems, identities, and proofs directly into working, verified, and idiomatic Python algorithms.

---

## 📌 Full Release: All 24 Chapters Available (78 Notebooks)

All **24 chapters** (`Chapter-01/` through `Chapter-24/`, **78 interactive notebooks**) are now available and validated. For example, **Chapter 01 ("Logic, Sets and Mathematical Reasoning")** includes:

| Notebook | Focus & IT Application | Mathematical Foundations | Estimated Time | Status |
| :--- | :--- | :--- | :--- | :--- |
| [`01-boolean-access-control.ipynb`](Chapter-01/01-boolean-access-control.ipynb) | Security access control rules & decision trees | Propositional logic, truth tables, conjunction, disjunction, negation | 15–20 min | **Ready** |
| [`02-de-morgans-laws-verifier.ipynb`](Chapter-01/02-de-morgans-laws-verifier.ipynb) | Multi-factor authentication condition simplification | De Morgan's laws, logical equivalence ($\equiv$), exhaustive truth tables | 15–20 min | **Ready** |
| [`03-set-operations-and-filtering.ipynb`](Chapter-01/03-set-operations-and-filtering.ipynb) | Database record filtering & role-based access control | Sets, subsets ($\subseteq$), intersection ($\cap$), union ($\cup$), difference ($\setminus$) | 20–25 min | **Ready** |
| [`04-quantifiers-and-implication.ipynb`](Chapter-01/04-quantifiers-and-implication.ipynb) | System invariant audits & material implication verification | Universal ($\forall$) & existential ($\exists$) quantifiers, implication ($P \Rightarrow Q$), contrapositive | 20–25 min | **Ready** |

Explore the notebooks in [`Chapter-01/`](Chapter-01/).

---

## 🗺️ 24-Chapter Curriculum Map

The complete curriculum spans 24 chapters across 5 pedagogical parts, mapping directly to the primary textbook:

```
Part I: Foundations & Discrete Mathematics (Chapters 01–06)
Part II: Linear Algebra for Data and AI (Chapters 07–10)
Part III: Probability, Information & Statistical Inference (Chapters 11–14)
Part IV: Calculus, Optimisation & AI Models (Chapters 15–21)
Part V: IT Systems, Cryptography & Algorithms (Chapters 22–24)
```

### Complete Chapter Index

| Chapter | Title | Core Mathematical Topics | Target Applications |
| :--- | :--- | :--- | :--- |
| **Part I** | **Foundations & Discrete Mathematics** | | |
| **01** | **Logic, Sets and Mathematical Reasoning** | Propositions, truth tables, De Morgan's laws, quantifiers, implication | Access control, invariant checking, query filtering |
| **02** | How Computers Represent Numbers | Positional number systems, two's complement, IEEE 754 floating-point | Precision boundaries, catastrophic cancellation, `float16` vs `float32` |
| **03** | Numbers for Computing | Modular arithmetic, wrap-around rings, complex plane, roots of unity | Hash tables, circular buffers, 2D planar rotation |
| **04** | Functions, Graphs and Equations | Linear, polynomial, exponential, log, activations, bisection root-finding | Sigmoid, Tanh, ReLU, Softmax, neural layer bounds |
| **05** | Counting, Sequences and Algorithm Growth | Arithmetic/geometric series, permutations, combinations, Big-O | Algorithm complexity benchmarking, search spaces |
| **06** | Geometry and Trigonometric Models | Euclidean/Manhattan metrics, unit circle, trigonometric identities | Spatial search, Transformer sinusoidal positional encodings |
| **Part II** | **Linear Algebra for Data and AI** | | |
| **07** | Vectors and Coordinates | Vector spaces, dot product, norm, unit vectors, orthogonality | Word embeddings, semantic vector arithmetic |
| **08** | Matrices and Linear Systems | Matrix operations, non-commutativity, Gaussian elimination, determinants | Linear solvers, system equilibrium, data transforms |
| **09** | Transformations and Computation | Linear maps, 2D/3D affine transforms, homogeneous coordinates | Computer graphics, camera pipelines, point cloud transforms |
| **10** | More Linear Algebra | Cosine similarity, vector projection, Gram–Schmidt, matrix rank, least squares | Recommendation ranking, linear regression normal equations |
| **Part III** | **Probability, Information & Statistical Inference** | | |
| **11** | Sampling and Confidence Intervals | Bernoulli trials, Law of Large Numbers, Central Limit Theorem, bootstrap | A/B test sample sizing, estimation intervals |
| **12** | Conditional Probability, Bayes & Random Variables | Bayes' theorem, prior/posterior, expectation, variance, discrete distributions | Fraud detection, diagnostic scoring, LLM temperature sampling |
| **13** | Information Theory, Entropy and Loss Functions | Shannon entropy, cross-entropy, Kullback–Leibler (KL) divergence | Classification loss surfaces, distribution shift detection |
| **14** | Statistical Testing and AI Evals | Two-proportion $z$-test, permutation tests, statistical power, Bonferroni | LLM evaluation benchmarks, model comparison significance |
| **Part IV** | **Calculus, Optimisation & AI Models** | | |
| **15** | Derivatives, Chain Rule and Numerical Stability | Finite differences, chain rule, LogSumExp, Riemann sums | Backpropagation mechanics, numerical stability in Softmax |
| **16** | Gradient Descent and Multivariable Optimisation | 1D/2D gradient descent, learning rates, Hessian curvature, momentum | Loss convergence, ill-conditioned valleys, local minima |
| **17** | Feature Scaling, Normalisation and Dimensionality Reduction | Min-Max scaling, Z-score, LayerNorm, RMSNorm, SVD-based PCA | Data preprocessing, Transformer layer normalization, PCA |
| **18** | Generalisation, Overfitting and Regularisation | Train/val/test splits, confusion matrices, ROC-AUC, $L_2$ weight decay | Model evaluation, overfitting diagnostics, regularisation |
| **19** | From Linear Models to Neural Networks | Simple/multiple linear regression, logistic regression, 2-layer MLP | Multi-layer perceptron training, XOR non-linear decision boundary |
| **20** | Embeddings, Vector Search (RAG) and Fine-Tuning (LoRA) | Cosine indexing, chunking strategies, LoRA rank decomposition | Retrieval-Augmented Generation, parameter-efficient fine-tuning |
| **21** | Mathematics of Transformers and Large Language Models | Self-attention mechanism, scaled dot-product, causal masks, top-$k$/top-$p$ | Transformer attention heads, autoregressive token generation |
| **Part V** | **IT Systems, Cryptography & Algorithms** | | |
| **22** | Graphs, Trees and Networks | Adjacency matrices, BFS/DFS, Dijkstra shortest path, PageRank | Network routing, dependency resolution, link analysis |
| **23** | Modular Arithmetic and Cryptography | Greatest Common Divisor (GCD), Extended Euclidean, Diffie–Hellman, RSA | Public-key encryption, secure key exchange |
| **24** | Recurrences and Divide-and-Conquer Algorithms | Divide-and-conquer recurrences, Master Theorem, Merge Sort, Binary Search | Recurrence relation analysis, algorithmic efficiency |

---

## 🚀 Usage Modalities

You can complete all exercises in this repository through either of two modalities:

### Modality 1: Google Colab (Zero-Install, Cloud-Based) — Recommended
- Every notebook features an **"Open in Colab"** badge at the very top.
- Simply click the badge to launch the notebook directly in your browser.
- No local Python installation or GPU is required.
- Standard libraries (`numpy`, `math`, `random`, `collections`) are pre-installed in the Colab runtime.

### Modality 2: Local Python Environment (JupyterLab / VS Code)
- Ideal for offline study, local version control, and IDE workflow.
- Requires **Python 3.10+**.
- Fast setup via virtual environment:
  ```bash
  python3 -m venv .venv
  source .venv/bin/activate  # macOS / Linux
  pip install -r requirements.txt
  jupyter lab
  ```
- Detailed, step-by-step instructions for Windows, macOS, and Linux are provided in [**QUICKSTART.md**](QUICKSTART.md).

---

## 📐 Pedagogical Structure of Every Notebook

Each interactive notebook is engineered around an evidence-based pedagogical template:

1. **Cell 1 — Header & Metadata**:
   - Notebook title, Colab badge, textbook section cross-reference, estimated completion time (15–25 minutes), and 2–3 precise learning objectives.
2. **Cell 2 — Clean Imports**:
   - Imports from standard library and NumPy only. Deterministic random seed (`np.random.default_rng(42)`) initialized when stochastic methods are used.
3. **Cell 3 — Mathematical Foundation & Context**:
   - LaTeX mathematical definitions, formulas, and real-world IT scenario context (e.g., access control policies, database query filters, network routers).
4. **Cell 4 — Scaffolded Starter Code**:
   - Functions with Python 3.10+ type annotations, comprehensive docstrings detailing inputs and outputs, `# TODO` implementation prompts, and `raise NotImplementedError(...)`.
5. **Cell 5 — Collapsible Hints**:
   - Dropdown `<details><summary>Hint</summary>...</details>` blocks providing incremental algorithmic hints without spoiling the complete answer.
6. **Cell 6 — Self-Check Assertion Suite**:
   - Built-in `assert` statements and automated validation tests that give you immediate feedback upon running your function.
7. **Cell 7 — "Think Deeper" Reflection**:
   - Conceptual questions prompting you to connect the code to edge cases, algorithmic complexity, security implications, or mathematical generalizations.

---

## ⚡ Technical Guidelines & Performance Constraints

- **Execution Speed**: Every notebook is designed to execute top-to-bottom on a standard CPU in **under 5 seconds**.
- **No Heavy External Datasets**: All matrices, truth tables, and datasets are generated algorithmically inline.
- **Reproducibility**: All random operations utilize explicit random seeds for 100% deterministic, reproducible behavior across runs.
- **Modern Python Standards**: All code adheres to PEP 8 standards, utilizes type hints (`tuple[bool, bool]`, `set[str]`, `np.ndarray`), and runs on Python 3.10 through Python 3.14.

---

## 🛡️ Academic Integrity Notice

- The student notebooks in `09.Maths-for-IT-Notebooks/` are intended for independent learning, lab tutorials, and coursework completion.
- Complete reference solutions, automated grading scripts, and marking rubrics are maintained separately in the faculty repository (`10.Maths-for-IT-Notebooks-Solutions/`).
- While discussing mathematical concepts with peers is encouraged, all submitted function implementations must be your own original intellectual work.
- Use of generative AI assistants: You may use AI tools to explain mathematical notation or debug syntax errors, but direct automated generation of exercise solutions is prohibited under course assessment policies.

---

*Course developed for ITSU1012 / ITSU1012R: Mathematics for Information Technology.*
