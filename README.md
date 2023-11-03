# PassGen
Password Generator: Django Password Generator
## Description
The Django Password Generator is a web application built with Django that allows users to generate random passwords. It includes a user interface for specifying password criteria such as length and character types and a backend for generating the passwords according to the specified criteria.

## Features
- Generate random passwords
- Customize password length
- Include options for different character sets (uppercase, lowercase, numbers, symbols)
- Installation

#To set up the project on your local machine, follow these steps:

1. Ensure you have Python installed on your system. The project is built with Django, which is a Python-based framework.

2. Clone the repository or download the project files to your local machine.

3. Navigate to the project directory and install the required dependencies using pip:

`pip install -r requirements.txt`

*(Note: The project might not include a requirements.txt file. If that's the case, you would need to install Django using pip install django)*

### Once the dependencies are installed, you can run the following command to start the Django development server:

`
python manage.py runserver
`

Open your web browser and go to http://127.0.0.1:8000/ to view the application.

## Usage
To generate a password, navigate to the password generation page, set your desired password criteria, and click on the generate button.

## Project Structure
- passgen/ - The main application directory containing the views, models, forms, and templates.
- passgenerator/ - The project configuration directory with settings and root URL configurations.
- db.sqlite3 - The SQLite database file for the project.
- manage.py - A command-line utility for interacting with the project.
