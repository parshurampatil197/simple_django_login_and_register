# Simple Django Login and Registration

Django project with basic user functionality.

## Screenshots

| Log In | Create an account | Authorized page |
| -------|--------------|-----------------|
| <img src="./screenshots/login.png" width="200"> | <img src="./screenshots/create_an_account.png" width="200"> | <img src="./screenshots/authorized_page.png" width="200"> |

| Password reset | Set new password | Password change |
| ---------------|------------------|-----------------|
| <img src="./screenshots/password_reset.png" width="200"> | <img src="./screenshots/set_new_password.png" width="200"> | <img src="./screenshots/password_change.png" width="200"> |

## Functionality

- Log in
    - via username & password
    - via email & password
    - via email or username & password
    - with a remember me checkbox (optional)
- Create an account
- Log out
- Profile activation via email
- Reset password
- Remind a username
- Resend an activation code
- Change password
- Change email
- Change profile
- Multilingual: English, French, Russian, Simplified Chinese and Spanish


## Requirements

Last tested successfully with Python 3.6.19 and Ubuntu 16.04\
Django==2.2\
[Django](https://www.djangoproject.com/): The web framework for perfectionists with deadlines (Django builds better web apps with less code).


## Quick Setup

1. Clone the project
```bash
https://github.com/parshurampatil197/simple_django_login_and_register.git
cd simple_django_login_and_register

```

2. Create a virtual environment and install django

```bash
  virtualenv venv --python=python3 ; 
  source venv/bin/activate; 

```

Install the dependencies needed to run the app:
```bash
  pip install Django==2.2
  pip install -r requirements. txt 

```


4. Initialize the database

```bash
  python manage.py makemigrations
  python manage.py migrate

```




Run the project

```bash
  python manage.py runserver

```

## Authors

- [@parshuram](https://github.com/parshurampatil197)
