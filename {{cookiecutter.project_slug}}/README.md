# {{cookiecutter.project_name}}
{{cookiecutter.description}}
<br/>Author : - {{cookiecutter.author_name}}

- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)

## Installation

Create an environment with python3.10 and use pip to install the required packages from requirements.txt
```bash
$ cd {{cookiecutter.project_slug}}/{{cookiecutter.project_slug}}
$ pip install -r requirements.txt
```

## Configuration
- Open file `.env`
- Configure your database
- Run makemigrations and migrate

## Usage
Run your django webserver
```bash
$ python manage.py runserver
```
