# MicroExpense

MicroExpense is a lightweight expense tracking application built with PHP and a custom micro MVC PHP framework. This framework is custom-built, applying Object-Oriented Programming (OOP) principles for efficient and maintainable code.

## Overview

MicroExpense provides a simple yet effective way to track expenses. Users can log in, add their expenses with details such as date, category, and amount, and view their expense history. The application offers a user-friendly interface and essential functionalities for managing personal or small-scale expenses.

## Features

- User authentication: Users can register, login, and manage their accounts securely.
- Expense tracking: Users can add, edit, and delete their expenses with details such as date, category, and amount.
- Expense categorization: Expenses can be categorized for better organization and analysis.
- History view: Users can view their expense history, including past expenses and summaries.

- Custom micro MVC PHP framework: The application is built on a custom micro MVC PHP framework, emphasizing simplicity and efficiency.

# Installation

To install MicroExpense, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/mokammeltanvir/MicroExpense.git
   ```
2. Navigate to the project directory:
   ```bash
   cd MicroExpense
   ```
3. Install dependencies using Composer:
   ```bash
   composer install
   ```
4. Configure the database connection by creating a `.env` file:
   ```bash
   cp .env.example .env
   ```
   Then, open the `.env` file and update the database credentials.
5. Run the database migrations:

   ```bash
   php cli.php
   ```

Note: Make sure you have PHP and Composer installed on your system before proceeding with the installation.

## Project View

![App Screenshot](microexpense.gif)

## Authors

- [@mokammeltanvir](https://www.github.com/mokammeltanvir)
