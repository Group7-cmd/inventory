# Inventory-Management

Django-based Inventory Management System

## Overview

This Inventory Management System is a web application built using Django that allows users to manage their inventory efficiently. It features functionalities for adding, updating, and tracking products, orders, and customers.

## Features

- **Product Management**: Add, edit, and delete products in the inventory.
- **Order Tracking**: Create, view, and update orders.
- **Customer Management**: Manage customer information and order history.
- **User Authentication**: Secure login and user management.
- **Responsive Design**: User-friendly interface accessible on various devices.


Ensure you have the following installed on your system:

- Python 3.8 or higher
- Django 4.0 or higher
- pip (Python package manager)
- Git (for cloning the repository)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Group7-cmd/inventory.git
   cd Inventory-Management
   ```

2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv myenv
   source myenv/bin/activate  # On Windows, use `myenv\Scripts\activate`
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply database migrations:**

   ```bash
   python manage.py migrate
   ```

5. **Create a superuser for the admin interface:**

   ```bash
   python manage.py createsuperuser
   ```

6. **Start the development server:**

   ```bash
   python manage.py runserver
   ```

7. **Access the application:**

   Open your web browser and navigate to `http://127.0.0.1:8000/`.


### Requirements

The project requires the following Python packages to be installed:

- Django
- django-filter
- pillow

Additional requirements can be found in the `requirements.txt` file.

### Configuration

**Database Configuration:**

By default, the project uses SQLite. You can change the database settings in `inventoryproject/settings.py`.


