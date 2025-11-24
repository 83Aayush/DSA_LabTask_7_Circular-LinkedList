# 🔄 Circular Linked List in Python

This program demonstrates the implementation of a **Circular Singly Linked List**, including:

- Inserting a node at the **end**
- Inserting a node at the **beginning**
- Displaying all nodes in circular order

A circular linked list is a variation of a linked list where the last node points back to the first node, forming a **closed loop**.

---

## 🧠 Key Concepts

### ✔ Circular Linked List
Unlike a normal linked list, the last node's `next` pointer points to the **head**.  
This allows continuous traversal without hitting `None`.

### ✔ Node Structure
Each node consists of:
- `data` → stores the value  
- `next` → points to the next node  

---

## 📂 Features Implemented

### 🔹 Insert at End
Adds a new node after the last node and links it back to the head.

### 🔹 Insert at Beginning
Adds a new node before the current head and updates the last node to point to the new head.

### 🔹 Display List
Traverses the list in a loop until it reaches the head again.

---

## ▶ How to Run the Program

1. Save the file as:

