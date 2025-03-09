
# Flask Item Selling Application

This repository contains the code for a simple Flask-based application for selling items. It demonstrates the core concepts of Flask, including user authentication, database management with SQLAlchemy, and item management.

## Features

- User authentication (sign up, login, and logout)
- Item listing with CRUD (Create, Read, Update, Delete) operations
- Basic form handling with Flask-WTF
- Database management using SQLAlchemy
- Password hashing with Flask-Bcrypt for security
- CSRF protection using Flask-WTF

## Technologies Used

- **Python 3.12+**
- **Flask**: A lightweight WSGI web application framework for Python
- **Flask-SQLAlchemy**: An ORM for Flask, which simplifies database management
- **Flask-Bcrypt**: For securely hashing passwords
- **Flask-WTF**: For handling web forms and CSRF protection
- **SQLite**: The database for this application

## Installation

### Prerequisites

- Python 3.12+
- pip (Python package installer)

### Steps

1. Clone this repository:

   ```bash
   git clone https://github.com/krish143434/flask-Ecommerce-.git
   ```

2. Navigate to the project directory

3. Create a virtual environment (optional but recommended):

   ```bash
   python3 -m venv venv
   ```

4. Activate the virtual environment:
   
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```

5. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Run the application:

   ```bash
   python run.py
   ```

7. Open a web browser and go to `http://127.0.0.1:5000/` to see the app in action.

## How It Works

1. **User Registration and Login**:
   - Users can register with their username and password.
   - Passwords are securely hashed using **Flask-Bcrypt**.
   - Once registered, users can log in and manage items.

2. **Item Management**:
   - Users can create new items, update them, or delete existing ones.
   - Each item has details such as name, price, and description.

3. **Database Management**:
   - The application uses **SQLAlchemy** for handling the database interactions.
   - All user and item data are stored in an SQLite database.

4. **CSRF Protection**:
   - **Flask-WTF** is used for form handling and ensuring CSRF protection.


This `README.md` file gives users a clear understanding of how to set up and use the Flask-based item selling application. Feel free to customize it further based on the specifics of the project!