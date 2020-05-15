<div align="center"><h1>  Django Connect With mysql database Setting </h1> </div>
<div align="center"> In this repo, I created django project with msysql database.you can my setting for mysql connection. </div>


Usage
-------
You can clone the project and run the following command to install: 

```bash
$ git clone https://github.com/rahulcs754/django-with-mysql-.git
```

*I consider, You have already installed virtualenv and pip.*

*First of all, create a virtualenv in a working directory*

```bash
$ virtualenv virtualenv_name
```
*after that you have to activate virtualenv machine by using the below command*

In linux
--------
```bash
$ source virtualenv_name/bin/activate
```
In Windows
------------
```bash
$ source virtualenv_name/Scripts/activate
```


 Installing list of dependencies to file
-----------------------------------------
```bash
pip install -r requirements.txt
```

create database  
```bash
$ python manage.py migrate
```

 create admin username and password
```bash
$ python manage.py createsuperuser
```

run main file 
-------------
```bash
$ python manage.py runserver
```

*Note  : Make sure you cd into the *clone* folder before performing the command above.*


Stack
python3



