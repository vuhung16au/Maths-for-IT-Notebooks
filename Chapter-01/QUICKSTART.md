# Chapter 01 Quickstart Guide

This quickstart guides students through completing the Chapter 01 Python exercises on **Logic, Sets and Mathematical Reasoning**.

---

## 🛠️ Execution Options

### Option A: Google Colab (Zero-Install)
1. Open the [Chapter-01 README](README.md) or click the **Open in Colab** badge in Cell 1 of any notebook.
2. If prompted, select **Copy to Drive** so your changes are saved to your personal Google Drive.
3. Step through cells sequentially using `Shift + Enter`.

### Option B: Local Jupyter Environment
1. Ensure Python 3.10+ is installed on your workstation.
2. From the repository root, install the required packages:
   ```bash
   pip install -r 09.Maths-for-IT-Notebooks/requirements.txt
   ```
3. Launch JupyterLab or open the notebooks in VS Code:
   ```bash
   jupyter lab 09.Maths-for-IT-Notebooks/Chapter-01/
   ```

---

## 📝 Workflow Instructions

1. **Read Mathematical Context (Cells 1 & 3):** Study the formal definitions, notation, and worked examples from Chapter 1 of the textbook before writing code.
2. **Review Environment Setup (Cell 2):** Run Cell 2 to import standard modules (`itertools`, `typing`) and NumPy.
3. **Implement Functions (Cell 4):**
   - Replace each `# TODO` comment and `raise NotImplementedError("Complete this TODO")` block with your implementation.
   - Do not modify function signatures, parameter names, or return type annotations.
4. **Consult Hints if Needed (Cell 5):** Expand the collapsible `<details>` hint block for operator precedence or algorithmic tips.
5. **Run Self-Checks (Cell 6):** Execute the assertion cell. If any assertion fails, review the error traceback and refine your logic. When all tests pass, a confirmation message will print.
6. **Think Deeper (Cell 7):** Reflect on the discussion question connecting the discrete mathematical theory to systems architecture, cybersecurity, and database query engines.
