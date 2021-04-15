# Bookle : project #5
## Library Management system

## Project details :
- NAME : Radhika Patwari
- ROLL : 18CS10062
- Lab test 2 : DBMS : CS43002
- 6/4/2021

## Demo of the project :
Demo of the application can be found at the youtube link :  https://www.youtube.com/watch?v=AOJYbG1oEPY

## Technology used :
- Django
- Sqlite3 database
- Html
- Css
- Js
- Bootstrap

## Project Structure :

```
|- lab_test/ 
	|- manage.py : Django manager main file
	|- requirements.txt : Containing packages required to run this application
	|- lab_test/
		|- settings.py : settings for all apps created in this project
		|- urls.py : directing urls used by various applications
		|- __init__.py : declaring lab_test as a python package
		|- asgi.py : projectc configuration
		|- wsgi.py : used during deployment of project on server 
	|- myapp/
		|- __init__.py : declaring my_app as a python package
		|- urls.py : directing urls within the application
		|- apps.py : declaring this folder as the application
		|- models.py : contain definition of tables used in the application
		|- views.py : contain funtionalities to be performed in the application 
		|- admin.py : registering tables with django admin site
		|- tests.py : containg tests if required (useful in deployment)
		|- static/  
			- contain front end tools : css, images, js scripts
		|- templates/
			- contain html pages
```

## Testing :
- Used virtual python environment on a linux machine

## Setting Up virtual Python3 environment
1.Follow the commands to create a environemnt "env" and activate it
```
sudo apt-get install python3.7-venv
python3.7 -m venv env
```

2.Activate the environment using the command below
```
source env/bin/activate
```
3.Install the required libraries in the virtual environment
```
pip3 install -r requirements.txt
```
4.To deactivate the environment,use
```
deactivate
```
## Setting up the project
1.Please follow the above steps to set up the virtual environment if you haven't already

2.Unzip the folder and the extracted main folder called 'lab_test' is created 

3.Activate the virtual environment from wherever you have made it
```
source env/bin/activate
```
3.Follow the below commands to set up the database with the required tables [directory 'lab_test' was created in step 2]
```
cd lab_test
python3 manage.py makemigrations
python3 manage.py migrate
```
4.Start the Django server using the below command
```
python3 manage.py runserver 
```
5.Follow the URL dispalyed on terminal and you will be directed to the website

 

