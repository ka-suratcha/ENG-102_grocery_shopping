# ENG-102_C_shop

## 📖 Overview
This project was created as part of **ENG-102: Computer Programming for Engineer**.
This project was created to put all of the basic programming concepts that were taught in the course to use. The entire program is written in a single `main` function because functions had not yet been covered in the course.

Simulating a **console-based grocery shopping system** is the aim of this project. Users can browse categories, select items, verify their choices, enter quantities, and then pay using the program. It shows how to use C's arrays, loops, conditional statements, input validation, and formatted output.

---

## ✨ Features
- **5 categories** of grocery items:
  - Vegetables
  - Fruits
  - Beverages
  - Garnishes
  - Snacks
- **10 items per category**, each with a fixed price.
- Shopping loop:
  - Choose a category (1–5).
  - Select an item (1–10) or go back (0).
  - Confirm the item and input the quantity.
  - Add items to the shopping list with automatic subtotal and tax calculation.
- **Error handling**: Invalid inputs are detected, and the user is prompted to re-enter.
- **Payment system**:
  - Calculates total including 8% tax.
  - Ensures payment covers the total.
  - Calculates and displays change.
- **Summary**: Prints a detailed receipt of all purchased items.

---

## 🧩 Flowchart
The shopping process is outlined in the flowchart below:

![Flowchart](FC_ENG-102_grocery_shopping.jpg)

## ▶️ Example Workflow
1. User selects a grocery category (e.g., Fruits).
2. User chooses an item (e.g., Apple) and confirms.
3. User inputs quantity (e.g., 3).
4. Program adds it to the shopping list, updates subtotal, and shows tax/total.
5. User decides whether to purchase another item or proceed to checkout.
6. At checkout, user inputs the amount paid, and the program calculates change.
7. A receipt is displayed with all purchases, subtotal, tax, total, and change.