# Daily Expense Analyzer

A console-based Java application for recording, viewing, sorting, and analyzing daily expenses.

## Features

- Add an expense with a category and amount
- Generate a unique expense ID
- Display all recorded expenses
- Sort expenses by amount from highest to lowest
- Search expenses by category
- Calculate the total expense and identify the highest expense
- Automatically load and save expense data in `expenses.txt`
- Validate categories and expense amounts

## Data Structures and Algorithms

This project is designed as a practical DSA exercise using:

- `ArrayList` to store expense records dynamically
- A linear search to find expenses by category
- Insertion sort to arrange expenses in descending order of amount
- Linear traversal to calculate totals and find the highest expense
- File I/O to provide persistent storage

## Project Structure

```text
dsa-project/
|-- DailyExpenseAnalyzer.java
|-- README.md
`-- expenses.txt
```

`expenses.txt` is created automatically after expenses are added or when the program exits.

## Requirements

- Java Development Kit (JDK) 8 or later

## Run the Project

From the project directory, compile and run the Java program:

```bash
javac DailyExpenseAnalyzer.java
java DailyExpenseAnalyzer
```

## Using the Application

When the program starts, choose one of the menu options:

```text
1 - Add Expense
2 - Display All
3 - Sort by Amount (high to low)
4 - Search by Category
5 - Total Expense
6 - Exit (save and quit)
```

### Example Expense

```text
Category: Food
Amount: 250
```

The expense is stored as:

```text
X101|Food|250
```

## Data Storage Format

Expenses are saved in `expenses.txt` using pipe-separated values:

```text
expense-id|category|amount
X101|Food|250
X102|Travel|120.50
```
