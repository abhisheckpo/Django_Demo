Welcome to the Django Demo project! This is a beginner-friendly Django project to help you get started with web development using Django.

Prerequisites

Before you begin, ensure you have the following installed:

Python 

pip 

virtualenv 

Django 

Installation

Follow these steps to set up and run the project on your local machine:

1. Clone the Repository

git clone https://github.com/abhisheckpo/Django_Demo.git
cd Django_Demo

2. Create a Virtual Environment

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3. Install Dependencies

pip install -r requirements.txt

4. Run Migrations

python manage.py migrate

5. Create a Superuser

python manage.py createsuperuser

Follow the prompts to set up an admin user.

6. Start the Development Server

python manage.py runserver

Visit http://127.0.0.1:8000/ in your browser to see the app in action.


