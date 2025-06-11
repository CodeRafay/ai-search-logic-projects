# 🧠 ai-search-logic-projects(AI & Logic-Based Intelligent Systems)

This repository includes four diverse and educational projects demonstrating the power of **AI**, **logic-based reasoning**, **machine learning**, **search algorithms**, and **constraint satisfaction** in solving real-world and game-inspired problems.
---

# 🤖 AI Project Collection – Logic, Search, ML & Simulation

👨‍💻 Developed by **Rafay Adeel**

---

## 📁 Included Notebooks

### 1. 🏠 Predicting House Prices using Linear Regression and k-Nearest Neighbors (k-NN)
**File:** `Predicting House Prices using Linear Regression and k-Nearest Neighbors (k-NN).ipynb`

- Performs data exploration, preprocessing, and regression on the **California Housing dataset**.
- Trains and compares Linear Regression & k-NN models (k = 3 to 11).
- Evaluates models using **R², MAE, MSE, RMSE**.
- Visualizes:
  - Correlations
  - Predicted vs. Actual values
  - Feature importance (from Linear Regression)
- Saves plots:
  - `california_housing_eda.png`
  - `feature_importance.png`
  - `model_comparison.png`
  - `prediction_comparison.png`

---

### 2. 🧩 Sudoku Puzzle Solver using PL and FOL
**File:** `Sudoku Puzzle solver using PL and FOL.ipynb`

- Interactive Sudoku solver using:
  - **Propositional Logic (CNF + PySAT)**
  - **First-Order Logic (recursive backtracking)**
- Uses `tkinter` GUI to input and solve puzzles.
- Ensures rule satisfaction:
  - One digit per cell
  - No repeats in row/column/3×3 box

---

### 3. 🧪 Maze Escape – Save the Scientist using A*
**File:** `Maze Escape – Save the Scientist using A.ipynb`

- A `pygame` simulation where you help a scientist escape a dynamic 15×15 maze.
- Implements **A\*** for automatic mode and arrow keys for manual control.
- Features:
  - Randomly placed traps, walls, locks
  - Exit tile and real-time movement costs
  - Performance reporting (steps, memory, cost)
  - Auto-updating maze to simulate dynamic conditions

---

### 4. 🚦 Autonomous Smart City Traffic Signal Optimization using CSP
**File:** `Autonomous Smart City Traffic Signal Optimization using CSP.ipynb`

- Simulates a **4×5 smart city** traffic grid using:
  - Adaptive traffic lights
  - **CSP optimization** for dynamic conditions
- Manages cars, buses, and emergency vehicles.
- Considers:
  - 🚨 Emergency routes (hard constraint)
  - 🚦 Fair green time allocation
  - 🌧 Weather and 🕒 time-of-day effects
  - 🚶 Pedestrian wait management
  - 🔁 Green wave prioritization for vehicle chains

---

## 🛠 Prerequisites

Install all required Python packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn pygame python-sat
