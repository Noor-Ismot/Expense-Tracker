# 📝 Expense Tracker

A simple, command-line expense tracking program built in Python that helps users manage spending by category and view totals. The program uses a dictionary-based structure and saves data to a local file, ensuring your records are preserved even after closing the program.



## 🚀 Features 

**💰 Add Expenses:** Quickly input expense amount, category, and description.
**📊 View Total Expense:** Get a cumulative sum of all expenses.  
**🗂️ View Expenses by Category:** See a breakdown of spending organized by category. 
**💾 Persistent Storage:** Automatically saves and loads data from a json file using the JSON format.
**✅ Input Validation:** Ensures only valid numbers and non-empty categories are accepted.  




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

4.  **View summaries** of your expenses as needed.
5.  **Exit** the program when done.



## 🛠️ Code Highlights

**📂 JSON Integration:** Uses the `json` module to serialize and deserialize data, allowing for permanent storage in `expense.json`.
****🔁 Modular Logic:** Separate functions for loading, saving, and calculating totals make the code clean and maintainable.
**⚠️ Error handling:** Input validation ensures a smooth and error-free user experience.



## 🎯 Future Improvements

**📈 Visualizations:** Add charts or graphs to represent spending visually.
**🖥️ GUI Interface:** Create a user-friendly graphical interface.
**📅 Date Tracking:** Include timestamps for each expense to allow for weekly or monthly reports.
**🚨 Budget alerts:** Notify users when spending exceeds set limits.