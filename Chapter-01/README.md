# Chapter 01 — Logic, Sets and Mathematical Reasoning

Interactive Python exercise notebooks accompanying **Chapter 1** (`chapters/01-logic-sets-and-reasoning.tex`) of the *Maths for IT, ML, AI and LLMs* curriculum.

---

## 🎯 Learning Objectives

By completing this module, you will be able to:
1. Evaluate propositions using formal logical connectives ($\land, \lor, \neg$) and programmatic truth tables.
2. Formalize and simplify access-control policies and De Morgan's laws ($\neg(P \land Q) \equiv \neg P \lor \neg Q$, $\neg(P \lor Q) \equiv \neg P \land \neg Q$).
3. Perform fundamental set operations ($A \cap B, A \cup B, A \setminus B, A \Delta B$), distinguish elements from subsets, and implement database-style record filtering.
4. Implement predicates, evaluate universal ($\forall$) and existential ($\exists$) quantifiers, analyze material implication ($P \Rightarrow Q$), and discover counterexamples algorithmically.

---

## 📚 Notebook Directory

| Notebook | Topic | Book Reference | Est. Time | Colab Badge |
| :--- | :--- | :--- | :---: | :--- |
| [`01-boolean-access-control.ipynb`](01-boolean-access-control.ipynb) | Boolean Logic & Access Control | Section 1.1, Fig 1.2, Ex 1.6 | 15–20 min | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-01/01-boolean-access-control.ipynb) |
| [`02-de-morgans-laws-verifier.ipynb`](02-de-morgans-laws-verifier.ipynb) | De Morgan's Laws & Equivalence | Section 1.1, Ex 1.6 | 15–20 min | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-01/02-de-morgans-laws-verifier.ipynb) |
| [`03-set-operations-and-filtering.ipynb`](03-set-operations-and-filtering.ipynb) | Set Algebra & Record Filtering | Section 1.3, Fig 1.4–1.5, Ex 1.3 | 15–20 min | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-01/03-set-operations-and-filtering.ipynb) |
| [`04-quantifiers-and-implication.ipynb`](04-quantifiers-and-implication.ipynb) | Quantifiers, Implication & Counterexamples | Section 1.2 & 1.4, Fig 1.3 & 1.6, Ex 1.1, 1.2, 1.4, 1.5 | 20–25 min | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-01/04-quantifiers-and-implication.ipynb) |

---

## 🚀 Getting Started

### Option A: Cloud Execution via Google Colab
Click any **Open in Colab** badge in the table above or at the top of each notebook. No local installation is required.

### Option B: Local Execution via Virtual Environment
1. Clone or navigate to the repository root:
   ```bash
   cd <workspace-root>
   ```
2. Activate your virtual environment and install dependencies:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   pip install -r 09.Maths-for-IT-Notebooks/requirements.txt
   ```
3. Launch JupyterLab or your preferred notebook editor:
   ```bash
   jupyter lab 09.Maths-for-IT-Notebooks/Chapter-01/
   ```
4. Complete the `# TODO` sections in each notebook and verify that all self-check assertions pass.
