# neobistodoproject
Installation
Clone the repository to your local machine:

https://github.com/Adokkka/neobistodoproject.git

Steps and commands for Linux machine are the same but use python3 instead of python.

Create and activate a virtual environment (optional but recommended):

python -m venv venv

source venv/bin/activate   # On Windows: venv\Scripts\activate

Install the required dependencies:

cd neobistodoproject-main/todo

pip install -r requirements.txt

Apply migration to setup the database:

python manage.py makemigrations

python manage.py migrate

Start the development server:

python manage.py runserver

Open your web browser and navigate to http://localhost:8000/ to access the Todo app.
