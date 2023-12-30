# Instagram Clone using HTML , CSS, JavaScript, Django

### Basic django project setup:
```
django-admin startproject instaclone
```

### Change the directory:
```
cd instaclone
```

### Create any app in django:
```
python manage.py startapp post
```

### Make changes in ```settings.py``` file:
- ```import os```
- Configure your app in InstalledApp var.
- Under *TEMPLATES* variable in *DIRS* join ```templates``` folder with **BASE_DIR**.
- ```os.path.join(BASE_DIR,"templates")```  


### Working with static files:
```
STATICFILES_DIRS = [
    os.path.join(BASE_DIR, 'static')
]

STATIC_ROOT = os.path.join(BASE_DIR, 'staticfiles')

MEDIA_URL = '/media/'

MEDIA_ROOT = os.path.join(BASE_DIR, 'media')
```

### Make Migrations in Models:
```
python manage.py makemigrations
```

### Migrate the changes:
```
python manage.py migrate
```

### Create Super user:
```
python manage.py createsuperuser
```
# Instagram Clone with Django

This project is an Instagram clone built using Django. It includes various features commonly found in social media applications. Below is a detailed overview of the project features:

## 1. Basic Project Setup

- Set up a Django project and configured the necessary settings.
- Installed required dependencies and packages.

## 2. Listing Out Posts on Home Page

- Implemented functionality to display posts on the home page.

## 3. Database and Model

- Defined a database model to store information about posts, users, likes, comments, and more.

## 4. Django Forms

- Utilized Django forms for handling user input and form validation.

## 5. Post Details Using Function-Based Views

- Created views to display detailed information about a post.

## 6. Create Like and Dislike Function

- Implemented the ability for users to like and dislike posts.

## 7. Save the Post Function

- Developed a feature that allows users to save posts for later viewing.

## 8. User Profile in Django

- Implemented user profiles to display user-specific information.

## 9. Display Follow Count, Post Count, Following Count

- Showcased user statistics including follow count, post count, and following count on user profiles.

## 10. Create Follow and Unfollow User Function

- Enabled users to follow and unfollow other users.

## 11. Create Edit Profile Function

- Implemented a profile editing feature for users to update their information.

## 12. Comment and Reply Function

- Enabled users to leave comments on posts and reply to existing comments.

## 13. Chat App and Message Function

- Implemented a real-time chat application with messaging functionality.

## 14. Search Functionality

- Developed a search feature to allow users to find other users and posts.

## 15. Login and Registration

- Implemented user authentication with login and registration functionality.

## How to Run the Project

1. Clone the repository:

    ```bash
    git clone https://github.com/samagra44/Instagram_Clone_With_Django.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Apply migrations:

    ```bash
    python manage.py migrate
    ```

4. Run the development server:

    ```bash
    python manage.py runserver
    ```

5. Access the application at [http://localhost:8000](http://localhost:8000).

Feel free to explore and use the application as you would with Instagram!

## Contribution

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-new-feature`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-new-feature`.
5. Submit a pull request.

Thank you for contributing!
