# Binary Optimization Problem: Facility Location

## 👤 Author

| Name            | Role              | LinkedIn                                      |
|-----------------|-------------------|-----------------------------------------------|
| Jason Emmanuel  | Data Scientist | [linkedin.com/in/jasoneml](https://www.linkedin.com/in/jasoneml/) |

## 📌 Overview

This project tackles a **Binary Optimization Problem** in the context of **Facility Location Planning**. The aim is to determine **which potential store location(s)** a company should open to **minimize the total transportation cost** while ensuring **every customer is served by exactly one store**.

The project is implemented using:

- **Python** with the **PuLP** linear programming library
- **Microsoft Excel Solver** (as an alternative method)

![image](https://github.com/user-attachments/assets/68123761-49be-46ba-accf-6b7bb1467b77)

---

## 🧠 Problem Statement

A retail company has identified **five possible store locations** (L1–L5) and serves **twenty customers** (C1–C20). The company wants to decide **which store(s) to open** such that:

- Each customer is assigned to **exactly one** store.
- The **total transportation cost** from stores to customers is **minimized**.

This problem falls under the category of **combinatorial optimization** and is solved using **Binary Integer Programming (BIP)**.

---

## 🔢 Mathematical Formulation

### Decision Variables

![image](https://github.com/user-attachments/assets/f528b5ce-8184-454c-b7c6-eac8b8b4be00)

### Objective Function

![image](https://github.com/user-attachments/assets/c2540d5c-5180-4f0c-9881-ef438d721abf)

### Constraints

![image](https://github.com/user-attachments/assets/2001eccb-7644-48bc-be98-01e7f94a8724)

---

## ✅ Optimization Results

| Location | Status               |
|----------|----------------------|
| L1       | Not Optimal Location |
| L2       | ✅ Optimal Location   |
| L3       | Not Optimal Location |
| L4       | Not Optimal Location |
| L5       | Not Optimal Location |

---

## 🛠️ Tools and Libraries

| Tool / Library | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| **Python**     | Main programming language used for implementing the optimization model.     |
| **PuLP**       | A linear programming library in Python for modeling and solving LP/BIP problems. |
| **pandas**     | Used for handling and manipulating tabular data (optional for cost matrix input). |
| **Jupyter Notebook** | Interactive coding environment used to run and present the model.         |
| **Excel Solver** | Built-in Excel tool used to solve optimization problems for validation and comparison. |

---

## 📦 Dependencies

To run the notebook, install the following Python packages:

```bash
pip install pulp pandas
```
