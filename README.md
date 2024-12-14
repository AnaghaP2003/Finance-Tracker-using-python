# Finance Tracker using python

## What the Project Does
This project implements a **Finance Tracker** application using Python. It allows users to manage their personal finances effectively by tracking their transactions, categorizing expenses, and calculating the remaining budget. Users can analyze spending patterns and ensure their expenses stay within a predefined budget. The project leverages **Object-Oriented Programming (OOP) principles** to create a modular, reusable, and extendable application structure.

## Why the Project is Useful?
- **Expense Tracking**: Users can add transactions with details such as date, category, description, and amount.
- **Budget Monitoring**: The project helps users track total spending and determine whether they are exceeding their budget.
- **Categorized Insights**: Users can retrieve transactions by specific categories, making it easy to analyze spending habits.
- **OOP Principles**:
  - **Encapsulation**: The budget, transactions, and operations are encapsulated within the `FinanceTracker` class, ensuring better organization and data security.
  - **Modularity**: Methods such as `add_transactions`, `get_transactions`, and `get_budget_balance` are self-contained, allowing for easier maintenance and updates.
  - **Reusability**: The class structure is reusable for different budget scenarios, making it versatile for personal and professional financial management.

## How Users Can Get Started with the Project?

1. Prerequisites
Install Python and the Pandas package using command:
  ```bash
  pip install pandas

2. Running the Project
Clone the repository and Run the script in a Python environment.

3. Usage
Add a transaction: For example, 
obj.add_transactions("Jan 1st, 2025", "Metro", "Recharge", 500)

View transactions: For example, 
obj.get_transactions()
obj.get_transactions(category="Food")

Check budget balance: Add transactions and check your remaining budget after spending. For example, 
obj.get_budget_balance()








