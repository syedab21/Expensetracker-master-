# Personal Expense Tracker
## Overview

This is a personal expense tracker web application built using Django. It allows users to log their expenses, categorize them, and provides automated expense categorization and future expense prediction features. This README.md file provides instructions for setting up and running the application on your local machine, as well as some additional information about its features and usage.

## Features

- **Expense Logging**: Easily log your daily expenses, including the date, description, amount, and category.

- **Automated Expense Categorization**: The application uses machine learning algorithms to automatically categorize expenses based on their descriptions. This makes it easier to track and manage your spending.

- **Future Expense Prediction**: The application provides predictions for future expenses based on your spending history. This can help you plan your budget more effectively.

- **User Authentication**: Users can create accounts and log in to securely manage their expenses.

## Setup

To run this application locally, follow these steps:

1. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

3. Create a superuser account to access the admin panel:

   ```bash
   python manage.py createsuperuser
   ```

4. Start the development server:

   ```bash
   python manage.py runserver
   ```

5. Open your web browser and go to `http://localhost:8000` to access the application.

## Usage

1. Create a new account or log in using your superuser account.

2. Start logging your expenses by clicking the "Add Expense" button.

3. Fill in the expense details, including the date, description, amount, and category. You can also leave the category empty, and the application will attempt to automatically categorize it.

4. View your expense history, categorized expenses, and future expense predictions on the dashboard.

5. To access the admin panel, go to `http://localhost:8000/admin/` and log in with your superuser credentials. From the admin panel, you can manage users, categories, and view the database.

