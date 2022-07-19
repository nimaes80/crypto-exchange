# Cryptocurrency exchange website

This Project was writen in Django (for backend) and React (for frontend)

Any suggestion you give us can make our app better.


Quick Start
You need to run backend and frontend separately. To do that first we run backend then frontend

Run Backend
First we need to create virtual environment for backend

pip install virtualenv
python -m virtualenv -p python3 .env
for Window users

.env/Lib/activate

for Linux users

source .env/bin/activate

for MacOS users

I don`t Know neutral_face

After creating virtual environment we need to install requirements & initialize server. To do that You need to go to the backend folder and run the following code there

pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py collectstatic
python manage.py createsuperuser
Now you need enter your Name & Email & password after that run server with python manage.py runserver

Run frontend
To run frontend head to exchange-interface folder and run commands blow

npm install
npm start
or you can run it by yarn

TODO
 - [ ] Create frontend
 - [ ] Add Limit
 - [ ] Add bank gateways
 - [ ] Add OAuth
 - [ ] Add better algoritm to do transactions
 - [ ] Create backend
 - [ ] Add transactons algorithm
 - [ ] Add endpoints
 - [ ] Connect to pool