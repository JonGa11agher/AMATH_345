# AMATH 345
Interactive Notebooks for **AMATH 345: Data Driven Mathematical Models**, Fall 2025

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
| 03 | `Tutorial_03_ODEs` | Initial value problems, Forward Euler, RK2, the damped pendulum |
| 04 | `Tutorial_04_Optimization` | Gradient descent in 1D and on the Rosenbrock function |
| 05 | `Tutorial_05_SVD` | The geometry of the SVD, and low-rank image compression |
| 06 | `Tutorial_06_Penalized_Least_Squares` | p-norm penalties, and total variation inpainting |
| 07 | `Tutorial_07_Sparse_Recovery` | Basis pursuit, soft thresholding and ISTA on the Olivetti faces |
| 08 | `Tutorial_08_Curve_Fitting` | Michaelis–Menten: linearization vs nonlinear least squares |
| 09 | `Tutorial_09_ODE_Parameter_Estimation` | Fitting a damped harmonic oscillator by gradient descent |
| 10 | `Tutorial_10_Neural_Networks` | Building and training a single-hidden-layer approximator in PyTorch |
| 11 | `Tutorial_11_Width_vs_Depth` | The same budget of neurons as one wide layer vs four narrow ones |
| 12 | `Tutorial_12_Neural_ODEs` | ResNets as Forward Euler; learning a vector field with `torchdiffeq` |
| 13 | `Tutorial_13_DMD` | Dynamic mode decomposition of vortex shedding behind a cylinder |
| 14 | `Tutorial_14_SINDy` | Sparse identification of the Lorenz system |
| 15 | `Tutorial_15_Koopman` | Delay embedding, Koopman regression, and intermittent forcing |

**Every package the tutorials need is in `requirements.txt`**, including `scikit-learn`,
`torchdiffeq` and `pysindy` for Tutorials 07, 12 and 14. Step 3️⃣ above installs all of
them, so no notebook installs anything itself.

Tutorial 13 additionally needs the cylinder-flow dataset (`CYLINDER_ALL.mat`), which is too
large to ship here — download it from the DMD book website and drop it into `Data/`.

Data assets live in `Data/`, and the notebooks reach them as `../Data/`.

---

💡 **Tip:** When finished, deactivate the virtual environment:  
`deactivate`
