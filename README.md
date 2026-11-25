# AMATH 345
Interactive Notebooks for **AMATH 345: Data Driven Mathematical Models**, Fall 2026

---

## 📚 Setup Instructions

### 1️⃣ Install Python
Ensure you have **Python 3.x** installed:  
`python --version`

---

### 2️⃣ Create a Virtual Environment
It is recommended to use a virtual environment to isolate project dependencies:  
`python -m venv venv`

Activate the environment:

**Windows (PowerShell)**  
`venv\Scripts\Activate`

**macOS / Linux**  
`source venv/bin/activate`

---

### 3️⃣ Install Jupyter and Requirements
With the virtual environment activated and in the same directory as `requirements.txt`:  
`pip install --upgrade pip`  
`pip install jupyter`  
`pip install -r requirements.txt`

---

### 4️⃣ Launch Jupyter Notebook
`jupyter notebook`

---

### 5️⃣ Open and Run Notebooks
In the Jupyter interface, open the `Tutorials/` folder and run the cells. The tutorials are numbered to be worked through in order, but each one runs on its own.

---

## 🗂️ Tutorials

| # | Notebook | What it covers |
|---|---|---|
| 01 | `Tutorial_01_Linear_Algebra` | Matrix operations in NumPy, decompositions, the p-norm unit ball |
| 02 | `Tutorial_02_Change_of_Basis` | Similar matrices and diagonalization, seen as a change of basis |
| 03 | `Tutorial_03_Optimization` | Gradient descent, learning rates, and optimization of the Rosenbrock function |
| 04 | `Tutorial_04_SVD` | SVD geometry, image compression, and PCA with eigenfaces |
| 05 | `Tutorial_05_Penalized_Least_Squares` | Ridge regression, p-norm geometry, and image recovery with total variation |
| 06 | `Tutorial_06_Sparse_Recovery` | Sparse face reconstruction, basis pursuit, and comparison of ISTA and FISTA |
| 07 | `Tutorial_07_Curve_Fitting` | Linearized and nonlinear curve fitting, update rules, and convergence comparisons |
| 08 | `Tutorial_08_ODEs_and_Parameter_Estimation` | Euler/RK2 integration review, pendulum animation, and interactive logistic/oscillator parameter estimation |
| 09 | `Tutorial_09_Neural_Networks` | Sigmoid neurons as basis functions (1D and 2D) and universal approximation; PyTorch training loops; a wide (1 × 400) vs deep (4 × 20) network with matched parameter counts |
| 10 | `Tutorial_10_Neural_ODEs` | An introduction to Neural ODEs, the connection between RES-Net and Euler-Stepping, and the connection to Neural ODE |

**Every package the tutorials need is in `requirements.txt`**
Step 3️⃣ above installs all of
them, so no notebook installs anything itself.

Data assets live in `Data/`, and the notebooks reach them as `../Data/`.

---

💡 **Tip:** When finished, deactivate the virtual environment:  
`deactivate`
