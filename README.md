# annette_project

This project is a simple Django Web Application. It portray's Annete Tech Course Offerings page and give details about individual courses that are offered. 

Also includes a search api for searching specific course contents. 


## Requirements:
Python 3.5 or a higher version must be installed on the host machine 
A suitable version can be downloaded from https://www.python.org

NB: On Windows Operating Systems, python must be added to System PATH

After a successful python installation, open the cmd on windows or the terminal on linux and run the command;

  	pip install virtualenv

This will install the virtualenv library which is used to create separate virtual environments for development.
After a successfull virtual environment installation, change directory to your preffered location (preferably desktop), open cmd/terminal and run the command;
	
		virtualenv venv

This will create a virtual environment.Activate the virtual environment using one of the following approaches;

	On Windows, from the same directory, run the command;
		venv\scripts\activate

	On linux systems, from the same directory, run the command;
		source venv/bin/activate

After successfully activating the virtual environment, install the project's requirement packages which is in the requirements.txt file using the command;
		pip install -r requirements.txt

After installing the packages, run the command;
		python manage.py runserver

The local development server will start and be accessible on port: 127.0.0.1:8000
Open your web browser and type the port addressto view the project site.
