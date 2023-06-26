Create a Virtual Environment and Activate it.
Open your Terminal/Command Prompt on the project’s root folder.
Install the Requirements: 
#    pip install -r requirements.txt.
Then, make database migrations: 
#    python manage.py makemigrations
#    python manage.py migrate
And finally, after a successful migration run the application: 
#    python manage.py runserver

# python manage.py createsuperuser

UserName: admin1
pass: admin