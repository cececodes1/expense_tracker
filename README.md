Expense Tracker

The Expense Tracker is a simple command-line application that allows users to track their expenses. The application will let users type their expense category and amount inside the terminal. It'll then save that expense entry to a file. And finally, read the file to summarise the expense totals for that month.

Features

- User input for expense name, amount, and category
- Expense categories: Food, Home, Work, Fun, and Misc
- Expense data is saved to a CSV file
- Summary of expenses by category
- Total spent and remaining budget calculation
- Daily budget calculation based on remaining days in the month

Usage

- Run the application by executing the main.py file.
Follow the prompts to enter expense name, amount, and category.
- Saves the expense data to a CSV file named expenses.csv.
- Displays a summary of expenses by category, total spent, remaining budget, and daily budget.

Files

- main.py: The main application file that contains the logic for getting user input, saving expenses to a file, and summarizing expenses.
- expense.py: The file that defines the Expense class used to represent individual expenses.
- expenses.csv: The file where expense data is saved.

Requirements

- Python 3.x
- calendar and datetime modules
