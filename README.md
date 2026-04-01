# DataFlow Pro - NileMart ETL Engine

## 📌 Overview
DataFlow Pro is a high-performance Python ETL (Extract, Transform, Load) engine designed for NileMart Inc.  
It cleans, structures, and optimizes messy sales and employee data to be efficiently consumed by Power BI dashboards.

---

## 🎯 Features

### Phase 1 – Query Optimizer (Sorting & Searching)
- Implements Bubble Sort, Insertion Sort, Selection Sort, Merge Sort, Quick Sort, and Python's built-in Timsort.
- Linear Search, Binary Search, and `bisect` for fast transaction lookup.
- Optimizes raw sales data retrieval for large datasets.

### Phase 2 – Applied Steps Tracker (Linked List)
- Tracks ETL transformation steps (like Power Query's "Applied Steps").
- Supports adding, undoing, and redoing steps using singly and doubly linked lists.

### Phase 3 – DAX Formula Parser (Stack)
- Evaluates custom KPI formulas in postfix notation.
- Implements stack using both array and linked list structures.
- Ensures correct operator precedence and parentheses handling.

### Phase 4 – Live Data Buffer (Queue)
- Buffers live streaming sales data from branches.
- Demonstrates FIFO queue using Python list, linked list, and `collections.deque` for performance comparison.

### Phase 5 – Hierarchical Matrix Builder (Trees)
- Binary Search Tree (BST) to store unique Customer IDs for fast Power BI relationships.
- N-ary tree to model the NileMart organizational chart.
- Recursive roll-up calculation to sum sales for managers and VPs.

---

## 🛠️ Installation

1. Clone the repository:

```bash
git clone https://github.com/esraasherif-tech/dataflow_pro.git
cd dataflow_pro