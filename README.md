# online-voting-system

Open your Terminal/Command Prompt on the project’s root folder.
Install the Requirements: pip install -r requirements.txt.

Install gtk3 to avoid go-object error:
https://github.com/tschoonj/GTK-for-Windows-Runtime-Environment-Installer/releases/download/2022-01-04/gtk3-runtime-3.24.31-2022-01-04-ts-win64.exe

Then, make database migrations: python manage.py makemigrations
python manage.py migrate
And finally, after a successful migration run the application: python manage.py runserver
At last, open up your favorite web browser
Go to URL "http://127.0.0.1/8000"
For the Admin Login credentials, you have to create one with a superuser.