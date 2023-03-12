# Chat App
This is a real-time chat application built with Django, Channels, and WebSocket. It allows users to create chat rooms and communicate with each other in real-time.

## Features
* Users can create accounts
*  Users can log in and log out
* Users can search for other users
* Users can add other users as friends
* Users can chat in realtime with friends
* Users can create a chatroom
* Users can join a chatroom with the uuid of it
* Users can chat in realtime with other membersin a chatroom
* Users can add status updates to their home page
* Users can add  images to their account and these are accessible via their home page
* correct use of models and migrations
* correct use of form, validators and serialisation
* correct use of django-rest-framework
* correct use of URL routing
* appropriate use of unit testing

## Getting Started

### Prerequisites
* Python 3.6+
* Django 3.1+
* Channels 3.0+

### Installation
1. Change into the project directory
    cd AWD_FinalProject
2. Create a virtual environment:
    python -m venv env
3. Activate the virtual environment:
    On Windows:
        env\Scripts\activate
    On macOS or Linux:
        On macOS or Linux:
4. Install the dependencies:
    pip install -r requirements.txt
5. Run the migrations:
    python manage.py migrate
6. Start the development server:
    python manage.py migrate
7. Access the application at http://localhost:8000/

## Usage
1. Register a new account or login with an existing account.
2. Update user profile
3. Search other users with username and add friends
4. Create a new group chat room or join an existing one.
5. Start chatting with other users in real-time.

## Test
    python manage.py test
