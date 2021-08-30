# Our First Topic is about Django Models

![model](https://www.askpython.com/wp-content/uploads/2020/07/Django-Models-1024x546.png.webp)



## What the Django models are?

- Python objects used in Django web applications to access and manage data tand also to define the structure of stored data.

## Designing the LocalLibrary models

- When designing the models we have to separate models for every group of related information.

- Then we need to define relationships that can be one to one (OneToOneField), one to many (ForeignKey) and many to many (ManyToManyField).


## Model definition

- The are defined in **application's models. py file.**

- They are implemented as subclasses of the database models

- It can include :

1-Fields; each one represents a column of data that we want to store in one of our database tables and the field types can also take arguments that further specify how the field is stored or can be used.

  - There are many types of fields, including fields for different types of numbers (big integers, small integers, floats), booleans, URLs, slugs, unique ids, and other "time-related" information (duration, time, etc.)

2- methods ; in every model you should define the standard Python class method __ str __() to return a human-readable string for each object.
3- metadata ; to control the default ordering of records returned when you query the model type.

## Model management

- Once you've defined your model classes you can use them to create, update, or delete records, and to run queries to get all records or particular subsets of records.




# Our Next Topic is Django admin site

![admin interface](https://www.askpython.com/wp-content/uploads/2020/07/Django-Admin-Site.png)

- The Django admin application can use your models to automatically build a site area that you can use to create, view, update, and delete records.

- All you must do to add your models to the admin application is to register them

## Registering models 

- First, open admin.py in the catalog application

- Register the models by importing the models and then calls admin.site.register to register each of them.

## Logging in and using the site

- This part of the site displays all our models, grouped by installed application. 

- You can click on a model name to go to a screen that lists all its associated records.
- You can further click on those records to edit them. 
- You can also directly click the Add link next to each model to start creating a record of that type.
