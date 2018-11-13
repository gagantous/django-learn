# Django-learn

This project is just for educational purposes and for those who want to learn Django Framework.

# Required Packages
1. Python3
2. Python-pip
2. virtualenv

# Installation

1. Create a virtualenv using the following command
`virtualenv -p python3 django_learn_env` 

2. Activate the virtualenv
`source django_learn_env/bin/activate`

3. Install the required packages
`pip3 install -r requirements.txt`

4. Run Django migrations
`python3 manage.py migrate`

5. To run the Django server
`python3 manage.py runserver`

# Using the Django App

1. Open your browser to the URL: `127.0.0.1:8000`
you'll notice the following text: `Ini adalah halaman index test`

2. Edit the URL on your browser to this `http://127.0.0.1:8000/berita/`
you'll notice the following text: `Hello, World!`