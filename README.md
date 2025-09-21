# Grocery Store Inventory System

**Name**: Tarun Yadav  
**Roll No**: 2401350015  
**Course**: BTech CSE FSD  

## 📝 Project Description
This project is a menu-driven Inventory Management System for a grocery store, implemented in C++. It allows users to manage stock items by adding, deleting, and searching for products. It also supports viewing inventory in different formats and identifying rarely restocked items using sparse representation.

## 💻 Technologies Used
- **Language**: C++  
- **Data Structures**: Vectors (dynamic arrays), Sparse Representation  
- **Concepts Applied**:  
  - Single and multi-dimensional arrays  
  - Row-major and column-major ordering  
  - Time and space complexity analysis  

## 📦 Features
- Add new items to inventory with user input  
- Delete items by Item ID  
- Search items by Item ID or Name  
- Display price and quantity in row-major or column-major format  
- Show rarely restocked items (quantity ≤ 2) using sparse representation  
- Menu-driven interface for easy interaction  

## 🧮 Functionality Overview

### Inventory Item ADT
- `insertItem()` – Adds a new item to the inventory  
- `deleteItem()` – Removes an item by its ID  
- `searchItem()` – Finds an item by ID or name  

### Inventory Management System
- `displayPriceQuantityTable()` – Shows price and quantity in selected format  
- `showSparseItems()` – Displays items with low stock  

## 📊 Complexity Analysis
Each function includes comments explaining:
- **Time Complexity** (e.g., O(n) for search and delete)  
- **Space Complexity** (based on vector usage and item count)

## 🚀 How to Run
1. Open the code in any C++ IDE (e.g., CodeBlocks, Visual Studio, or use g++ compiler).
2. Compile the program.
3. Run the executable.
4. Use the menu to interact with the system.

## 🎯 Learning Objectives
- Understand and implement array-based data structures in C++  
- Apply row-major and column-major ordering for data organization  
- Use sparse representation for optimizing storage  
- Analyze performance of functions in terms of time and space  

## 📁 File Structure
- `main.cpp` – Contains the complete source code for the inventory system  
- `README.md` – Project overview and instructions  

---
