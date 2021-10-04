This is a Kanban board that is implemented using Flask, where you can create your account and persist data into a SQL database.

Project Directory

|   kanban.db
|   kanban.py
|   models.py
|   readme.md
|   requirements.txt
|   test.py
|
\---templates
        home.html
        login.html
        register.html

## For Windows
python -m venv env
env\Scripts\activate

pip install -r requirements.txt
python kanban.py

### For unit tests
python test.py
