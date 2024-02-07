# Chat-Application
Chat Application based on Django Channels and Websockets.

To start the web application you need to use some commands.

1. first clone this project using - git clone https://github.com/Somvit09/Chat-Application.git
2. then make a virtual env and activate it.
3. then install the modules using - pip install -r requirements.txt
4. use migrations and migrate for the database -
    python3 manage.py makemigrations
    python3 manage.py migrate
5. you need to create 2 users, as of we can create superusers too for testing this Application
    python3 manage.py createsuperuser
    - and then give credentials of the superuser.
6. launch this web application using localhost:8000 in 2 incognito windows.
7. login with the 2 super user credentials.
8. send message  to each other and you are good to go.

