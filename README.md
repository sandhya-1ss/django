*Django Chat Application

This is a real-time chat application built with Django that allows users to sign up, log in, and communicate with other registered users.

*Features
User signup and login
Collapsible menu displaying all registered users
Initiating chat with other users
Storing user data and chat messages in a database
Retrieving and displaying past conversations
Utilizing WebSockets for real-time chat functionality
Providing a user-friendly and functional chat interface
Use a WebSocket for chat application.
Ensure the chat interface is user-friendly and functional.

*Prerequisites:

Python 
Django framework

*Getting Started: 
  Open your terminal or command prompt:

Navigate to the directory where you want to create your project 
*Create the virtual environment:
->python -m venv .venv  
*Activate virtual environment
->.venv\Scripts\activate

Create a Django Project:

django-admin startproject chat_app
Create a Django App:

cd chat_app
python manage.py startapp chat
Add the chat app to INSTALLED_APPS in settings.py

python manage.py makemigrations
python manage.py migrate
This command will apply all pending migrations for all your apps.

Run the Development Server:

This starts the local development server:

python manage.py runserver
This will usually start the server at http://127.0.0.1:8000/
