**Clone the repo
git clone https://github.com/shawn-carter/DjangoTemplate

*You can rename this folder to whatever you like at this point (we'll call it NewProject)
Windows PowerShell: move DjangoTemplate NewProject
Linux: mv DjangoTemplate NewProject

*cd into your folder
cd NewProject

*Create a virtual environment
python -m venv venv

*Activate the virtual environment
Windows: venv\scripts\activate
Linux: source /venv/bin/activate

*Install requirements
pip install -r requirements.txt

*Create a new Superuser
python manage.py createsuperuser

*Run server
python manage.py runserver
