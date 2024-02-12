# Django Project

This Django project implements user registration and authentication using Django Rest Framework (DRF) with JWT-based authentication.

## Getting Started

Follow the instructions below to get a copy of the project up and running on your local machine.

### Prerequisites

Before you begin, ensure you have the following installed on your system:
- Python (version 3.6 or higher)
- Django
- Django Rest Framework
- Git

### Installation

1. Clone the repository to your local machine:

    https://github.com/Sebifrancis1935/assesment-task


2. Navigate to the project directory:

    cd assesment-task

3. Install the project dependencies using pip:

    pip install -r requirements.txt

4. Run the Django migrations to create the database schema:

    python manage.py makemigrations
    python manage.py migrate

5. Create a superuser to access the Django admin site:

    python manage.py createsuperuser

6. Start the Django development server:

    python manage.py runserver


7. Access the application in your web browser at [http://localhost:8000/](http://localhost:8000/)

## Usage

- To register a new user, make a POST request to `/api/register/` with the user's email and password.
- To log in, make a POST request to `/api/login/` with the user's email and password. You will receive a JWT token in the response.
- Use the JWT token to access protected resources by including it in the Authorization header of your requests.

## Contributing

If you'd like to contribute to this project, you can follow these steps:

1. Fork the repository on GitHub.
2. Clone your fork of the repository to your local machine.
3. Create a new branch for your changes.
4. Make your changes and commit them to your branch.
5. Push your changes to your fork on GitHub.
6. Submit a pull request from your branch to the main repository.

## Acknowledgments

- Thanks to the Django and Django Rest Framework communities for their excellent documentation and resources.
