# Django Documentation Project


## Description
This project follows the official [Django Documentation Tutorial](https://docs.djangoproject.com/en/4.2/intro/tutorial01/) to create a basic polls app. The purpose of this project is to learn Django best practices and keep my version control skills sharp.


## Installation
### 1. Clone the Repository
```sh
git clone http://github.com/KadonDEngle/django-docs-project

cd django-docs-project
```
### 2. Install Dependencies
```sh
pip install -r requirements.txt
```
### 3. Database Setup
```sh
python manage.py migrate
```

### 4. Create a Super User
Access the admin panel at `localhost:8000/admin`. You can create a super user account using: 
```sh
python manage.py createsuperuser
```

### 5. Run the Development Server
```sh
python manage.py runserver
```


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.