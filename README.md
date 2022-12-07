# Django Basic Commands a developer Should be know
All These commands based on Windows OS

1. Installing Virtualenv 
    
    ```
    pip install virtualenv
    ```
    
2. Creating Virtualenv
    ```
    virtualenv (environment name)
    ```
    
3. Activating Environment:
    ```
    (environment name)\Scripts\activate  (Windows OS)
    ```

4. Deactivating Environment:
    ```
    venv\Scripts\deactivate.bat (Windows OS)
    ```

5. Installing django:
    ```
    pip install django
    ```

6. Starting Django Project:
    ```
    django-admin startproject (project name) .
    ```

7. Running Django Project:
    ```
    python manage.py runserver
    ```

8. Creating app:
    ```
    django-admin startapp (app name)
    ```

9. Migrating the Model(Step-1):
    ```
    python manage.py makemigrations
    ```

10. Migrating the Model(Step-2):
    ```
    python manage.py migrate
    ```

11. Translating  ORMS into SQL statements:
    ```
    python manage.py sqlmigrate (migrationfilename)
    ```
12. Activating Python Shell:
    ```
    python manage.py shell
    ```
