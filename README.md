flaskCamel
==========

**flaskCamel** is a flask microframework based re-usable application which have various common
features included i.e. *User Registration/Login, User Profile, Facebook Login (oAuth),
Verification Email, Password Reset and Simple Admin Interface, Twitter Boostrap* etc.

One can use this application to add their own logic on top of it, without 
worrying about implementation of common features required in web applications.

#### Steps to follow:
- Clone repo.
- Create Virtualenv.
- Install dependencies `pip install -r requirements.txt`
- Change config settings in `flaskcamel/config.py` such as `MAIL_USERNAME`, `MAIL_PASSWORD` and DB settings if you wish.
- Also change facebook application settings in `flaskcamel/views.py` to use valid credentials.
- Start application using: `python manage.py`
- Visit `http://localhost:5000` to access the application.

**Note:** *You're most welcome to add/improve flaskCamel's features. Suggestions are loved too.*
