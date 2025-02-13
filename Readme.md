### Virtual Environment

windows:
```bash
python -m venv marvin-food-api
```

Unix/MacOS:
```bash
python -m venv marvin-food-api
```

This will set up a virtual environment, and create a folder named "marvin-food-api" with subfolders and files, like this:

myworld
__Include
__Lib
__Scripts
__pyvenv.cfg

Then you have to activate the environment, by typing this command: 

Windows:
```bash
source marvin-food-api/Scripts/activate
```

Unix/MacOS:
```bash
source marvin-food-api/bin/activate
```

### Django is installer using pip, with this command:

Windows
```bash
py -m pip install Django
```

Unix/MacOS:
```bash
python -m pip install Django
```

### Django Create Project

Once you have come up with a suitable name for your Django project, like mine: marvin_food_api, navigate to where in the file system you want to store the code (in the virtual environment), I will navigate to the marvin-food-api folder, and run this command in the command prompt:

```bash
django-admin startproject marvin_food_api
```

Django creates a marvin_food_api folder on my computer, with this content:

marvin_food_api
    manage.py
    marvin_food_api/
        __init__.py
        asgi.py
        settings.py
        urls.py
        wsgi.py

### Run the Django Project

py manage.py runserver