# django-stepbystephisto

#### Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

#### Prerequisites
What things you need to install the software and how to install:
1. Python 3
2. Django 2.1.7


#### Installing
Here is a step by step series of examples that tell you how to get a development env running

+  Create or go to the desired folder destination

+  Create a virtual environment:

```
virtualenv venv
```

+  **__In case you use Python 2.7__**

   Change the version of Python the virtual environemnt is using with this command:
   
```
virtualenv --python=/usr/bin/python3.6 venv
```
   Change the destination file if needed.

+ Activate the environment:

```
. venv/bin/activate
```

If it worked, terminal prompt should be similar to this:

```
(venv) User@computer-UX430UAR:~/Documents/django-stepbystep$
```

+  Clone the repository to the destination folder

```git
git clone https://github.com/pedrogritter/django-stepbystep.git
```
+ Install required dependencies by running:

```
pip install Django==2.1.7
```

#### Deployment
~~This project is deployed on [Heroku](https://www.heroku.com/) over [here](https://project-guru.herokuapp.com/)~~

To deploy this on a live system enter the following command:

```
python manage.py runserver
```
A development server should be running at http://127.0.0.1:8000/



## Built With

[Django 2.1.7](https://www.djangoproject.com/)- Python Web framework used

[Vue.js](https://vuejs.org/) - Progressive Javascript framework

[Bulma](https://bulma.io)- CSS Framework

