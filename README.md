# Flask-Python-SQLite3-Project
Music Playlist Project using Python, Flask framework and SQLite3 as a database

This micro services are developed to create a music library where users can be created. Number of songs can be added. Also, user wise playlist can be created with the description for each of the tracks.

*This project is developed using FlaskAPI, python, Sqlite3, foreman, tavern

Micro-services can be tested using Postman. Details about request/response details cab ne found in the file "Music_Microservices_Part-1_Documentation". 



To Run all Micro-services execute below command on terminal after navigating to the folder you have downloaded the project (assuming python is already installed):

Step 1: Create an environment using below commands,

	mkdir myproject
	$ cd myproject
	$ python3 -m venv venv

Step 2: Activate the environment using below command,

	source ~/.virtualenvs/myvenv/bin/activate

Step 3: Install Tavern

pip3 install tavern

pip3 install tavern[pytest]

Step 4: Install Configobj

sudo python3 -m pip install configobj

Sqlite:

To install and run you can follow the instruction given here - 
https://www.sqlitetutorial.net/download-install-sqlite/

OR follow below instruction-

Step 1: Download sqlite-shell-win32-*.zip from below link-
https://www.sqlite.org/download.html

Step 2: Create folder "sqlite" in the drive you want to keep sqlite and extract downloaded zip here.

Step 3: Open the command prompt and go to the folder of sqlite in you drive. Now type sqlite3, hit enter. you are all set. 

After successful installations, open Terminal/ Command Prompt and hit below command by navigating to the folder where the project is downloaded.

Step 1: foreman start


Step 2: To Test all micro services:

	python3 app.py test
