# Django-blog-application
This blogs project allows the user to publish their blogs in the application. In this Django App, user initially need to register in and login to post their blogs. There are different features added in this application. Users can update their profile, can search through the blogs based on title of the post, Shows latest posts in the sidebar. The comments features allows a reader to post their comment for a post, can also remove, approve and edit it.

# Running the Project Locally
First, clone the repository to your local machine:

git clone https://github.com/prashver/Django-blog-application.git
Install the requirements:

pip install -r requirements.txt
Create the database:

python manage.py migrate
Finally, run the development server:

python manage.py runserver
The project will be available at 127.0.0.1:8000.
