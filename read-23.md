# read-23
### 18 june 2020
# [table of contents](https://h-griffin.github.io/reading-notes-401/)

# reading
- [Django Custum User Model](https://learndjango.com/tutorials/django-custom-user-model)
it is important to decide if you are using a custom user model or not before you start your project, because it will change how you begin your project. when setting up your server you **do not migrate** until after you have set up your user model and registered with admin. this is important because the default is not a custom user, and it is more difficult to convert or change than it is to jsut start over. the steps are similar to creating a regular django project however when adding the installed app, you also add to auth user model, this will not be in the settings file so you will have to manually insert ```AUTH_USER_MODEL = 'appName.CustomUSer``` at the bottom of the settings file. import and create things to make a CustomUser Class. to create the custom user the user will need a form to fill out, so you eill have to make a forms.py file and create classes to create and change the user form. you will also need to register this new custom user class in teh admin.py file to ensure the app can see the files. **now migrate** all of the necessary validations and forms have been created to do no harm when migrating. now fill out your templates to give the user the forms in their appropriate views.

## Videos
Choose one:

- [Creating a Custom User Moel](https://www.youtube.com/watch?v=eCeRC7E8Z7Y&t=59s)
- [Abstract User, User Profile and Signals in Django](https://www.youtube.com/watch?v=EudKs1HPUfE)

## Bookmark/Skim
- [Substituting a custom User model](https://docs.djangoproject.com/en/3.0/topics/auth/customizing/#auth-custom-user)

