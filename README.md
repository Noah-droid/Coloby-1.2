# Coloby

A research media web-application with Django.

## Features :

<li>Sign Up, Login, OAuth 2.0(Google, Github), Logout, Forgot Password</li>
<li>Public Profile view</li>
<li>Create, Edit, Delete Posts with customized text, pictures and links</li>
<li>Like, Comment / Reply, Save and Search posts</li>
<li>Follow and Unfollow users to view their posts</li>
<li>Friend Request</li>
<li>Notifications</li>
<li>Chats using websockets</li>
<li>Video Calls</li>

## Demo (Not yet active)





## Adding env variables

- Add env variables to ".test.env" and rename it to ".env"


- Add agora app_id to .env and to https://github.com/Ronik22/Django_Social_Network_App/blob/main/blog/static/blog/js/streams.js#L2

## Installation

```bash
    $ python -m venv venv
    $ source venv/Scripts/activate
    (venv) pip install -r requirements.txt
    (venv) cd Django_Social_Network_App
    (venv) python manage.py makemigrations
    (venv) python manage.py migrate
    (venv) python manage.py createsuperuser
    (venv) python manage.py runserver
```




## Running Tests

To run tests, run the following command

```bash
  python manage.py test
```

