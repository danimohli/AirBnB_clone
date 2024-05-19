# AirBnB Clone - The Console

#Description#

Welcome to the AirBnB clone project! This project is the first step towards building a full web application that mimics the functionality of the AirBnB platform. In this initial phase, we create a command interpreter to manage our AirBnB objects. The console allows us to create, retrieve, update, and destroy objects, and serves as the foundation for future enhancements, including HTML/CSS templating, database storage, API integration, and front-end development.

##Command Interpreter##

The command interpreter provides a way to interact with the backend of our AirBnB clone. It functions similarly to a shell but is tailored for managing specific objects like users, places, and states.

###How to Start It###

*Clone the repository:*
   ```sh
   git clone https://github.com/danimohli/AirBnB_clone.git
   cd AirBnB_clone

**Make the console script executable:**
   chmod +x console.py
***Run the console:***
   ./console.py

####HOW TO USE####
The console supports several commands to manage AirBnB objects:

create: Creates a new instance of a class.
	(hbnb) create <class_name>
show: Shows an instance based on class name and id.
	(hbnb) show <class_name> <id>
destroy: Deletes an instance based on class name and id.
	(hbnb) destroy <class_name> <id>
all: Shows all instances of a class, or all instances if no class is specified.
	(hbnb) all [<class_name>]
