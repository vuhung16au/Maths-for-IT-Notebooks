# Student Quickstart Guide: Getting Started with Maths for IT Notebooks

This guide provides step-by-step instructions for launching and completing the interactive Python notebooks. You can choose between **Option A (Google Colab)** for immediate cloud execution without any local installation, or **Option B (Local Environment)** for offline development in VS Code or JupyterLab.

---

## ⚡ Option A: Google Colab (Recommended — Instant Zero-Install)

Google Colab provides a free cloud-hosted Jupyter environment directly in your browser. All required dependencies (`numpy`, Python standard library) are pre-installed.

### Step 1: Open Any Notebook in Colab
1. Navigate to the chapter folder you want to work on (for example, [`Chapter-01/`](Chapter-01/)).
2. Click on any notebook file (e.g., `01-boolean-access-control.ipynb`).
3. Click the **"Open in Colab"** badge at the top of the notebook:
   
   [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vuhung16au/Maths-for-IT-Notebooks/blob/main/Chapter-01/01-boolean-access-control.ipynb)

### Step 2: Save a Copy to Your Google Drive
Colab opens notebooks in "view only / playground" mode initially. To preserve your work:
- Go to the menu: **File → Save a copy in Drive**.
- A new browser tab will open with your personal copy saved to your Google Drive (`MyDrive/Colab Notebooks/`).

### Step 3: Run Setup & Inspect Cells
- Run the first code cell (Cell 2) containing library imports (`Shift + Enter` or click the Play button).
- Read the mathematical definitions, theorems, and real-world IT scenario context.

### Step 4: Complete the Exercise
- Locate the code cell with the `# TODO` comment and `raise NotImplementedError(...)`.
- Delete the `raise NotImplementedError(...)` line.
- Write your Python implementation to compute the required mathematical logic.
- If you get stuck, expand the **Hint** dropdown in the preceding cell:
  ```html
  <details><summary>Hint</summary>...</details>
  ```

### Step 5: Verify with Self-Check Assertions
- Execute the assertion cell immediately following your function.
- If your implementation is correct, all assertions will pass silently or print a confirmation message:
  ```text
  All test assertions passed successfully!
  ```
- If an assertion fails, an `AssertionError` will show the specific test case that failed. Inspect your logic and re-run.

---

## 💻 Option B: Local Python Environment (JupyterLab / VS Code)

If you prefer to work offline or use your local editor, set up a dedicated Python virtual environment.

### Prerequisites
- **Python 3.10** or newer installed. Check your version:
  ```bash
  python3 --version
  # or on Windows:
  python --version
  ```
  *(Must report `Python 3.10.x` or higher)*

### Step 1: Clone or Navigate to the Repository
Open your terminal (macOS/Linux) or PowerShell/Command Prompt (Windows) and navigate to the student notebook directory:
```bash
cd 09.Maths-for-IT-Notebooks
```

### Step 2: Create a Dedicated Virtual Environment
Create a clean virtual environment named `.venv`:

- **macOS / Linux**:
  ```bash
  python3 -m venv .venv
  ```
- **Windows (PowerShell)**:
  ```powershell
  python -m venv .venv
  ```

### Step 3: Activate the Virtual Environment
- **macOS / Linux**:
  ```bash
  source .venv/bin/activate
  ```
- **Windows (PowerShell)**:
  ```powershell
  .venv\Scripts\Activate.ps1
  ```
  *(If script execution is disabled, run `Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass` first)*
- **Windows (Command Prompt)**:
  ```cmd
  .venv\Scripts\activate.bat
  ```

Once activated, your terminal prompt will display `(.venv)`.

### Step 4: Install Required Packages
Install the minimal dependencies using `pip`:
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

Verify your installation:
```bash
python -c "import numpy; import jupyter; print('Environment OK! NumPy:', numpy.__version__)"
```

### Step 5: Launch JupyterLab or VS Code

#### Launching JupyterLab:
```bash
jupyter lab
```
Your browser will open to the JupyterLab interface. In the left file browser, double-click:
```
Chapter-01/01-boolean-access-control.ipynb
```

#### Using Visual Studio Code:
1. Open the folder in VS Code:
   ```bash
   code .
   ```
2. Install the **Python** and **Jupyter** extensions from Microsoft if not already installed.
3. Open any `.ipynb` file in `Chapter-01/`.
4. In the top-right corner of the notebook editor, click **Select Kernel → Python Environments... → .venv (Python 3.x)**.

---

## 🧪 Workflow: How to Complete an Exercise

1. **Read & Understand**: Study the markdown cells explaining the mathematical definitions, truth tables, or set equations.
2. **Implement**: Replace `raise NotImplementedError("Complete this TODO")` with your implementation.
3. **Test**: Run the assertion code cell (`Shift + Enter`).
4. **Reflect**: Answer the "Think Deeper" question at the end of the notebook to consolidate your understanding of edge cases and computational complexity.

---

## ❓ Frequently Asked Questions & Troubleshooting

### Q: Why do I see `AssertionError` when running a test cell?
**A**: An `AssertionError` indicates that your function returned a result that does not match the expected mathematical truth table or output for a specific input. Review the function docstring for required data types and boundary conditions.

### Q: Why do I see `NotImplementedError`?
**A**: You have not yet replaced the starter template's `raise NotImplementedError(...)` statement with your own implementation.

### Q: How do I test all 4 notebooks in Chapter 01 locally?
**A**: Run the notebooks top-to-bottom within JupyterLab by selecting **Run → Run All Cells**. Every cell should execute without errors once your solutions are complete.

### Q: Can I install extra packages like PyTorch, Pandas, or Scikit-Learn?
**A**: All exercises in this curriculum are intentionally designed to be solved using **pure standard library Python and NumPy**. Avoiding external frameworks ensures you master the foundational mathematical algorithms from first principles!
