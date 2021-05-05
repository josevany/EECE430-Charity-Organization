# EECE 430 : Software Engineering Project

To run the project:

1- Go to https://github.com/josevany/EECE430-Charity-Organization

2- Clone the GitHub repo to your desired location

3- Unzip the folder website.zip

4- Configure the python environment

5- Install the libraries needed by the application to run:
	pip3 install Django

6- Navigate to the website folder
	cd website

7- Create the initial migration:
	python3 manage.py makemigrations

8- Execute the migration:
	python3 manage.py migrate

9- (OPTIONAL) Create a superuser (Preferably "admin"/"admin@mail.aub.edu"/"admin", and choose to allow weak passwords):
	python3 manage.py createsuperuser

10- Run the server:
	python3 manage.py runserver

11- Navigate in the browser to "127.0.0.1:8000" (Make sure the port is correct in cmd)

12- (OPTIONAL) To sign in to an admin account, navigate to "127.0.0.1:8000/admin" and login as "admin"/"admin", then navigate back to "127.0.0.1:8000", an Administrator tab will appear in the navigation bar

13- Feel free to roam in the project, create Contributors and Events, make donations, do CRUD operations on Database entries, and create and export reports to Excel

