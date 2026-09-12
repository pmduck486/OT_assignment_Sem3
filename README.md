# Operations Research: Optimization Algorithms

This repository contains robust, fully automated Python implementations for solving complex Operations Research problems using **Linear Programming** and **Transportation Models**.

## 🚀 Features
1. **The Big-M Simplex Solver:** Automatically converts inequalities to standard form, injects artificial/slack/surplus variables, and solves mathematically. Gracefully handles `Infeasible`, `Unbounded`, and `Alternative Optima` edge cases.
2. **Transportation Problem Solver (VAM + MODI):** Utilizes Vogel's Approximation Method for an initial Basic Feasible Solution (BFS), followed by the MODI method for optimization. Natively handles maximization, unbalanced matrices, degeneracy (maintaining $\epsilon$ spanning trees), and prohibited routes.

## 🛠️ How to Run This Project Locally

**1. Clone the repository**
```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
```

**2. Create a virtual environment**
```bash
# For Windows
python -m venv .venv
.venv\Scripts\activate

# For Mac/Linux
python3 -m venv .venv
source .venv/bin/activate
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

**4. Launch Jupyter Notebook**
```bash
jupyter notebook
```
Open `FINAL_OT_ASSGN.ipynb` in your browser and run all cells!
