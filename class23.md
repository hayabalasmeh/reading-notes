# Our topic is about Django Best Practices: Custom User Model

## As a general rule always use a custom user model for all new Django projects.


![custom user](https://www.geekinsta.com/content/images/2021/03/create-custom-django-user-model.jpg)


## How to implement this?

- First you need to know that there are two modern ways to create a custom user model in Django: AbstractUser and AbstractBaseUser.
 
- It's better to use AbstractUser .

- Creating our initial custom user model requires four steps:

    1- update config/settings.py

     - Within INSTALLED_APPS add accounts at the bottom. Then at the bottom of the entire file, add the AUTH_USER_MODEL config.

    2- create a new CustomUser model

    3- create new UserCreation and UserChangeForm

    4- update the admin



### Templates/Views/URLs

- Our goal is a homepage with links to log in, log out, and sign up.

#### How to implement this?

- Start by updating **settings.py** to use a project-level templates directory.

- Then set the redirect links for log in and log out, which will both go to our home template.

- Create a new project-level templates folder and within it a **registration** folder as that's where Django will look for the log in template.

- Put the **signup.html** template in there.