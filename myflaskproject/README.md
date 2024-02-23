# Flask Project README

## Overview

This is a Flask project that demonstrates how to build a simple web application using Flask. The application allows users to maintain a to-do list by adding, updating, and deleting tasks. It uses SQLAlcemy for the database 

## Getting Started

To get started, you'll need to have Python (3.8 or higher), pip and Flask installed on your computer. You can install Flask using pip:

```bash
pip install Flask

git clone https://github.com/technicaldifficulties666/flask-todo-app.git
cd myflaskproject
py -3 -m venv .venv
source .venv/Scripts/activate
pip install flask-sqlalchemy
```

To create a local database instance, start python shell
```bash
python
from app import db
db.create_all()
exit()
```

Run app on http://localhost:5000/
```bash
python app.py
