# 📝 Expense Tracker – Python Project

A simple, interactive expense tracking program built in Python that helps users manage daily spending by category and view totals. The program stores expenses in a dictionary, allowing for efficient categorization and retrieval. Users can continuously add expenses and view summaries until they choose to exit.

---

## 🚀 Features

* **💰 Add Expenses:** Quickly input expense amount, category, and description.  
* **📊 View Total Expense:** Get a cumulative sum of all expenses.  
* **🗂️ View Expenses by Category:** See how your spending breaks down.  
* **💾 Persistent Session Tracking:** Add multiple expenses in the same runtime session.  
* **✅ Input Validation:** Only accepts valid numeric amounts and non-empty categories.  

---

## ⚡ How It Works

1.  **Run the program** using Python:
    ```bash
    python expense_tracker.py
    ```

2.  **Follow the interactive menu:**
    * Add expense
    * View total expense
    * View expense by category
    * Exit

3.  **Enter your expenses** in the format:  
    `<Amount>, <Category>, <Description>`  
    *Example:* `1000, Food, Lunch at cafe`

---

## 🛠️ Code Highlights

* **📂 Dictionary-based storage:** Organizes expenses by category for fast lookup and aggregation.
* **🔁 Reusable functions:** Functions like `view_category_expense`, `view_total_expense`, and `add_expense` make the code modular and easy to extend.
* **⚠️ Error handling:** Input validation ensures a smooth and error-free user experience.

---

## 🎯 Future Improvements

* **💾 Data persistence:** Save expenses to a file (CSV/JSON) or database.
* **📈 Visualizations:** Add charts or graphs to represent spending visually.
* **🖥️ GUI Interface:** Create a user-friendly graphical interface using Tkinter or PyQt.
* **🚨 Budget alerts:** Notify users when spending exceeds set limits.