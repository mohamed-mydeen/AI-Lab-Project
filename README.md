# 🧠 AI Lab Project: Prolog Experiments & Expert Systems

![SWI-Prolog](https://img.shields.io/badge/SWI--Prolog-v9.2+-blue?logo=swi-prolog)
![AI](https://img.shields.io/badge/AI-Symbolic%20Logic-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A comprehensive collection of Symbolic Artificial Intelligence experiments and a complete Interactive Terminal-Based Recommendation System, all developed entirely in **SWI-Prolog**. 

This repository was created by **[mohamed-mydeen](https://github.com/mohamed-mydeen)** for the AI Laboratory coursework.

## 📂 Repository Structure

The project is divided into individual laboratory experiments and a comprehensive final project. All files have been optimized with clean and minimal naming conventions.

| Directory | Prolog File | Topic & Description |
|-----------|-------------|---------------------|
| `exp2/`   | `e2.pl`     | **Basics of Prolog:** Introduction to facts, rules, and basic queries. |
| `exp3/`   | `e3.pl`     | **Water Jug Problem:** State-space search solution for the classic puzzle. |
| `exp4/`   | `e4.pl`     | **4-Queens Problem:** Backtracking algorithm to solve constraint problems. |
| `exp5/`   | `e5.pl`     | **Monkey & Banana:** Logic programming approach to AI planning. |
| `exp6/`   | `e6.pl`     | **Breadth-First Search (BFS):** Graph traversal using a queue structure. |
| `exp7/`   | `e7.pl`     | **Depth-First Search (DFS):** Graph traversal using recursive backtracking. |
| `exp8a/`  | `e8a.pl`    | **List Flattening:** Recursive logic to manipulate and flatten nested lists. |
| `exp8b/`  | `e8b.pl`    | **Financial Model FOL:** First-Order Logic (FOL) financial advisory knowledge base. |
| `project/`| `proj.pl`   | **Final Project:** Interactive Product Recommendation System. |

---

## 🚀 The Final Project (`project/proj.pl`)

The capstone of this laboratory is a **Personalized Product Recommendation and Intelligent Store Placement System**. It uses dynamic predicates and rule-based logic to simulate an interactive store environment directly in the terminal.

**Key Features:**
- 🛒 **Store Inventory Navigation:** Browse items by distinct categories (Fast Food, Electronics, Grocery, etc.).
- 👤 **User Management System:** Create accounts, securely log in, and track dynamic purchase histories.
- 🤖 **Smart Recommendations:** Prolog engine infers recommendations based on complex cross-selling rules and past purchases.
- 📍 **Intelligent Store Placement:** Uses logic constraints to determine the optimal physical placement of items in a retail layout.

## 🛠️ How to Run

1. **Install SWI-Prolog:**
   Ensure you have SWI-Prolog installed on your machine.
   ```bash
   # Ubuntu/Debian
   sudo apt-get install swi-prolog
   ```

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/mohamed-mydeen/AI-Lab-Project.git
   cd AI-Lab-Project
   ```

3. **Running an Experiment (e.g., BFS):**
   Navigate to the experiment folder and load the file into the interactive SWI-Prolog terminal:
   ```bash
   cd exp6
   swipl e6.pl
   ```

4. **Running the Final Project:**
   ```bash
   cd project
   swipl proj.pl
   ```
   *Note: Once inside the SWI-Prolog terminal, type `start.` to launch the interactive UI.*

---

<p align="center">
  <i>Developed with ❤️ by Mohamed for the Artificial Intelligence Lab.</i>
</p>
