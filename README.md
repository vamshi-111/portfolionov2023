# portfolio
A website with my personal details and my projects designed with python and django

# creating a virtual environment so that your interpreter will get the dependencies associated with your package
python3 -m venv virtual_env

# activating the virtual environment
source virtual_env/bin/activate

# installing dependencies
pip3 install django
pip3 install dj_database_url
pip3 install -r requirements.txt

# db migration
python3 manage.py migrate
# whenever new changes are made to the module do
python3 manage.py makemigrations

# starting the server
python3 manage.py runserver
