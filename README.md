

## Project Setup

Please follow bellow steps to setup the project.

1. Create virtual environment
   ```
   python -m venv venv
   ```
2. Activate the virtual env
   ```
   .\env\scripts\activate
   ```
3. Install project dependencies
   ```
    pip install -r docs/requirements.txt
   
4. Create .env file in the project directory and add following,
   ```
SECRET_KEY =*!b&@i5v96600p574-z)fc5g%to!fmc0m_36u@1o%+%o&b3#=b
DEBUG = True
DB_NAME=mytask_db
DB_USER=root
DB_PASSWORD=Akkash9099
DB_HOST=127.0.0.1
APP_URL='http://localhost:8000/#'

6. Create django migrations
    ```
    python manage.py makemigrations user_auth
    
	python manage.py makemigrations
    ```
7. Migrate the SQL changes
   ```
    python manage.py migrate
