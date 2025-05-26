# Photography-Blog

A personal photography blog built with Django, designed to showcase a collection of photos, blog posts, and user interactions. This project allows users to browse image galleries, read posts, engage through comments, and a Read Later feature for saving content.

## Features
- Image galleries for showcasing photography with tags.
- Blog post creation and management for sharing stories behind the photos.
- Responsive design for seamless viewing on desktop and mobile.
- Comment system for user engagement.
- Read Later section for users to save posts for future viewing.

## Prerequisites
- asgiref==3.8.1
- Django==5.2
- gunicorn==23.0.0
- packaging==24.2
- psycopg2-binary==2.9.10
- sqlparse==0.5.3

## Administration
Create a superuser to access the admin panel using the following command:
python manage.py createsuperuser

## Usage
In this section we assume that the project is running locally on your system.
The Photography-Blog application provides the following features, accessible via the specified URLs:
- Home Page (/): Navigate to http://localhost:8000/ to view the main landing page, featuring an overview of the blog, with the last 3 posts shown on the panel.
- All Posts (/posts/): Go to http://localhost:8000/posts/ to browse a list of all blog posts, showcasing stories behind the photography with summaries and links to individual posts.
- Post Details (/posts/<slug>): Click on a post to read a specific blog post, view its associated images, and engage by adding comments (requires login for commenting).
- Read Later (/read-later): Navigate to http://localhost:8000/read-later to view and manage posts saved for later reading.
- Admin Panel: Go to http://localhost:8000/admin to access admin panel in order to manage posts, comments, tags and users at /admin (requires superuser login).

## Technologies
- Django (Backend framework)
- Python (Core language)
- PostgreSQL (Database)
- HTML/CSS (Frontend)
