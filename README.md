## Social Media Platform
The Social Media Platform is a Django-based web application that enables users to connect and interact with others. It provides a platform for users to create profiles, share posts, like and comment on posts, and engage in social networking activities.

## Features
User Authentication: Secure user authentication and registration system.
User Profiles: Users can create profiles with profile pictures and personal information.
Post Creation: Users can create, edit, and delete posts.
Likes and Comments: Users can like and comment on posts.
Friend Requests: Users can send and accept friend requests, connecting with others.
Activity Feed: Users have a personalized activity feed displaying posts from friends.


##  Getting Started
# Clone the Repository:

git clone https://github.com/Ymk74/Social-Media.git
cd Social-Media

# Install Dependencies:

pip install -r requirements.txt

# Database Migration:

python manage.py migrate
Run the Development Server:

python manage.py runserver
The application will be accessible at http://localhost:8000.

# Access the Admin Panel:
To access the Django admin panel, create a superuser account:

python manage.py createsuperuser
Visit http://localhost:8000/admin and log in with the superuser credentials to manage the application data.

## Technologies Used
Django
Django REST Framework
PostgreSQL (or your preferred database)
HTML, CSS, JavaScript (Frontend)
Bootstrap (Frontend styling)
