# django-chat-app
A realtime chat application using Django, Channels and Tailwind

## Requirements:
- Python3
- Django
- Daphne
- Channels

## Instructions:
Run these commands in your shell :
```bash
# Clone repository
git clone https://github.com/YahyaOukharta/django-chat-app django-chatapp
# Go to project folder
cd django-chatapp
# Init migrations
python3 manage.py makemigrations
# Apply migrations
python3 manage.py migrate
# Run application
python3 manage.py runserver
```

## Adding rooms
> Rooms are created manually from the django admin dashboard, here are the instructions:
- Create a super user using this command : ```python3 manage.py createsuperuser ```
- Go to http://127.0.0.1:8000/admin
- Login as superuser
- Add rooms