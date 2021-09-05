# Our Ffirst Topic is about Docker

## What is Docker?


![docker](https://www.docker.com/sites/default/files/social/docker_facebook_share.png)

- Docker is like Linux containers which are a type of virtualization.

- A way to implement Linux containers

## Containers vs Virtual Environments

- What are the limitations of virtual environment comparing to containers;

- Virtual environments are used to isolate Python software packages locally.

- They still rely on a global, system-level installation of Python albeit they can refer to the proper version. 

- Also we can’t run a production database or other services within virtual environments

- Containers are a lightweight alternative to Virtual Machines

## Let's get Know to some concepts and fundemental parts of Docker;

- **Images**; an image is a snapshot in time of what a project contains.
- Images are made up of one or more layers

- **Container** A container is a running instance of the image.

- **Dockerfile** is a list of instructions for creating an image.

- **docker-compose.yml** controls how to run the container.

# Our Second Topic is about API website creation using Django REST frameowrk

- Django REST Framework works alongside the Django web framework to create web APIs.

## Making Website using Traditional Django:

- We will follow the same steps we used to follow to create a Django project within it the app

## Extending the Website into web API with Django REST Framework

- Django REST Framework is added just like any other third-party app;

1- We install it "djangorestframework"

2- We added it to the INSTALLED APP config as a third part app

3- We will create an app, "api", to include all API-specific files for the entire project will live in a dedicated api app.

4- Then add it to INSTALLED_APPS.

5- URLs step, then add the URL configs

6- Create the **views.py** file which will relies on Django REST Framework’s built-in generic class views

7- Last we need to create the **serializer.py** file ,a serializer translates data into a format that is easy to consume over the internet, typically JSON, and is displayed at an API endpoint.

8- We will use the **Django REST Framework’s serializers class** to create our custom serializer class.
