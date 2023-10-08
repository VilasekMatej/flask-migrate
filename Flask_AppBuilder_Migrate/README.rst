Quick How to Example
--------------------

Simple contacts application with flask-migrate.

Download Application::

    $ git clone https://github.com/RybkaJakub/Flask_AppBuilder_Migrate
    $ python -m venv .venv
    $ . ./.venv/Scripts/activate
    $ pip install -r requirments.txt

Run it::

    $ flask fab create-admin
    $ flask db init
    $ flask db migrate
    $ flask db upgrade
    $ flask run

