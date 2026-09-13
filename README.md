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
(To be added as the course progresses)

**Every package the tutorials need is in `requirements.txt`**

Data assets live in `Data/`, and the notebooks reach them as `../Data/`.

---

💡 **Tip:** When finished, deactivate the virtual environment:  
`deactivate`
