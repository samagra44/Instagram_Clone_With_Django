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

This project is a fully functional Instagram clone developed using Django. The comprehensive set of features provides users with an experience similar to the popular social media platform. The project covers various aspects, starting with the basic project setup and dependencies installation. The application's core functionality includes listing posts on the home page, creating a robust database model to store user-related data, and implementing Django forms for user input and validation.

User interaction is a key focus of this clone, featuring post details views through function-based views, enabling users to like and dislike posts, and providing the ability to save posts for later. The user profile component is an integral part of the application, showcasing key statistics such as follow count, post count, and following count.

The social aspect of the platform is enhanced with the implementation of follow and unfollow functionalities. Users can also edit their profiles, adding a layer of personalization to their accounts. The commenting and reply system further promotes user engagement, allowing for interactive discussions on posts.

The project goes beyond the typical Instagram clone by introducing real-time chat functionality through a chat app. Users can send and receive messages in real-time, enhancing the overall social experience. The search functionality allows users to discover other users and posts easily.

To run the project, follow the provided steps in the README, which include cloning the repository, installing dependencies, applying migrations, and running the development server. Contributions to the project are encouraged, and the README outlines the steps for contributing.

This Instagram clone serves as a comprehensive project showcasing a wide array of Django features and functionalities, making it an excellent resource for learning and experimentation.

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
