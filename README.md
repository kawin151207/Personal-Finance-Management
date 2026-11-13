# Personal Finance Management System

A desktop-based personal finance management application built with Java Swing and AWT.

## Features

- Login screen
- Dashboard showing total income, expenses, available balance, and savings
- Add and track income
- Add expenses under categories
- Manage savings and savings goals
- View category-wise expense summaries
- Generate a financial report with expense history and date/time

## Requirements

- Java Development Kit (JDK) installed
- A Java IDE such as VS Code, IntelliJ IDEA, or Eclipse (optional)

## How to run

1. Open a terminal in the folder containing `PersonalFinanceManagement.java`.
2. Compile the program:

   ```bash
   javac PersonalFinanceManagement.java
   ```

3. Run it:

   ```bash
   java PersonalFinanceManagement
   ```

## Notes

- This project uses Java's built-in Swing and AWT libraries.
- The login screen currently checks that the username and password fields are not empty; it does not authenticate against stored user accounts.
- Data is held in memory while the application runs and is not saved to a database or file.
