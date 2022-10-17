# Blank App
Blank flask app based on flask tutorial

# Changes from flask tutorial
 - Added Bootstrap 4 lib instead of default style.css

# How to use
  1. Create virtual enviroment
  ```
  python3 -m venv venv
  ```
  2. Acitvate virtual enviroment
  ```
  . venv/bin/activate
  ```
  3. Install flask using pip
  ```
  pip install Flask
  ```
  or install using setup.py
  ```
   pip install e .
  ```
  4. Initialize database
  ```
  flask --app blank_app init-db
  ```
  5. Run Flask App
  ```
  flask --app blank_app --debug run
  ```
  6. App will be accessible through http://127.0.0.1:5000
# Resources
https://flask.palletsprojects.com/en/2.2.x/tutorial/
