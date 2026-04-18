# Expense-Tracker


DESCRIPTION:
  A Python CLI application to log, categorize, and analyze
  daily expenses. Generates bar and pie charts for monthly
  spending using Pandas-style CSV storage and Matplotlib.

HOW TO RUN:
  1. Install Python 3.7 or above
  2. Install dependencies:
       pip install matplotlib
  3. Run:
       python expense_tracker.py

FEATURES:
  - Add expenses with date, category, description, amount
  - View all expenses sorted by date
  - Monthly summary with category-wise breakdown
  - Bar chart + Pie chart saved as PNG
  - Search expenses by category
  - Delete expense by ID
  - Data saved in expenses.csv (auto-loads on restart)

CATEGORIES:
  Food, Transport, Shopping, Utilities, Health,
  Education, Entertainment, Other

CONCEPTS USED:
  - OOP (Classes, Encapsulation)
  - File I/O with CSV module
  - datetime module
  - defaultdict for aggregation
  - Matplotlib for data visualization
  - Input validation and error handling
  - Modular programming (methods per feature)

REQUIREMENTS:
  - Python 3.7+
  - matplotlib (for charts — app works without it too)

AUTHOR: Tanushi Singh,
TECHNOLOGY: Python 3

