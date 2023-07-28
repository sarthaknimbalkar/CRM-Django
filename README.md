# Client Relationship Management (CRM) Project

This is a Client Relationship Management (CRM) application built using Python and Django. The CRM project allows businesses to manage their client interactions, track customer data, and enhance customer relationships.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)

## Project Overview
The CRM application provides a user-friendly interface to manage client data. Users can perform basic CRUD (Create, Read, Update, Delete) operations on client information. The application is built using the Django web framework, which provides powerful tools for database management, authentication, and handling HTTP requests.

## Features
- Add new clients with their first name, last name, email, phone, address, state, zipcode.
- View a list of all clients with their basic information.
- Edit existing client information.
- Delete clients from the database.
- Update information of existing clients

## Requirements
- Python 3.11.4
- Django 4.2.3
- [See requirements.txt](requirements.txt) for additional dependencies.

## Installation
1. Clone the repository:

```
git clone https://github.com/sarthaknimbalkar/CRM-Django.git
cd crm-Django
```

2. Create and activate a virtual environment (recommended):

```
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

4. Perform database migrations:

```
python manage.py makemigrations
python manage.py migrate
```

## Usage
1. Start the development server:

```
python manage.py runserver
```

2. Open your web browser and visit `http://127.0.0.1:8000/admin/` to access the Django admin interface.
   - Use superuser credentials to log in (if not already created during migrations).

3. To access the CRM application, go to `http://127.0.0.1:8000/crm/`.

4. You can now perform CRUD operations on client data via the web interface.

## Contributing
Contributions to the project are welcome! If you find any issues or have suggestions for improvements, please feel free to create a pull request or open an issue.
