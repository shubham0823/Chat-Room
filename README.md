# Real-time Chat Application

This project is a real-time chat application built using Django and Channels. The front-end design is styled with Tailwind CSS. Below are the steps to set up and run the application.

## Features
- Real-time messaging
- User authentication
- Responsive design with Tailwind CSS

## Requirements
- Python 3.12
- Django 5.0
- channels==3.0.5


## Installation

### Clone the Repository
```sh
git clone https://github.com/yourusername/realtime-chat-app.git
cd realtime-chat-app
```

### Set Up a Virtual Environment
```sh
python -m venv venv
on linux , use 'source venv/bin/activate'
On Windows, use 'venv\Scripts\activate'

```

### Install Dependencies
```sh
pip install -r requirements.txt
```


### Run Migrations
```sh
python manage.py migrate
```

### Create a Superuser
```sh
python manage.py createsuperuser
```

### Run the Development Server
```sh
python manage.py runserver
```


## Usage
1. Open your browser and go to `http://127.0.0.1:8000/`.
2. Register a new user or log in with the superuser credentials.
3. Start chatting in real-time!

## Tailwind CSS Integration
Tailwind CSS is used for the front-end design.


## Acknowledgments
- Django: https://www.djangoproject.com/
- Django Channels: https://channels.readthedocs.io/
- Tailwind CSS: https://tailwindcss.com/


## Images
- https://drive.google.com/file/d/1ohX4-j1zS26eU6trlHffz-Is-BXbkraT/view?usp=sharing
---
