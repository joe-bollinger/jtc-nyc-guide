# jtc-nyc-guide

## Contributors:

1. Joe Bollinger: https://github.com/joe-bollinger
2. Walter Dunn Jr.: https://github.com/lavoing5762

This website is a guide to attractions in various NYC boroughs. Using the command "python -m venv django-env", on Windows, or "python3 -m venv django-env" on Mac a virtual environment for the app was initiated. The virtual environment was activated using "source django-env/bin/activate" on Unix/MacOS, or "django-env\Scripts\activate.bat" on Windows.

Django was previously installed using pip installer. The django server was managed using "python manage.py. This project was initiated with the django-admin function. After server activation and file mitigation we created the necessary html files, then created numerous paths to those files until website reflected the new pages and the assignment was completed.

To use this site:
1. From the command line enter: mkdir nyc
2. Enter the new directory: cd nyc
3. Clone the repository into the newly created directory: git clone https://github.com/joe-bollinger/jtc-nyc-guide.git 
4. Install virtual environment: python -m venv django-env
5. Start virtual environment: source django-env/bin/activate on Unix/MacOS, or django-env\Scripts\activate.bat on Windows.
6. Enter the jtc-nyc-guide directory: cd jtc-nyc-guide
7. Install necessary python libraries: pip install -r requirements.txt
8. Make necessary migrations: python manage.py makemigrations
9. Migrate migrations: python manage.py migrate
10. Start the server: python manage.py runserver
11. Open your browser to see the home page: http://127.0.0.1:8000/