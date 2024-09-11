# AirBnB Console Project

## Description
The AirBnB Console project aims to deploy a simplified version of the AirBnB website on a server. While not encompassing all features of the original platform, it incorporates fundamental concepts, serving as a foundation for higher-level programming and enhancing learning experiences.

## Command Interpreter
The Command Interpreter, akin to a Shell but tailored to specific use-cases, facilitates managing objects within the project. It enables the following capabilities:
- Creation of new objects
- Retrieval of objects
- Operations on objects
- Updating object attributes
- Deletion of objects

## Steps for Developing the Command Interpreter
This initial step is crucial as it sets the stage for subsequent projects, including HTML/CSS templating, database storage, API integration, and front-end development. The steps involve:
1. Setting up the console for object creation, aiding serialization/deserialization, and establishing the initial storage.
2. Creating HTML files for enhancing user interface and visualization.
3. Implementing MySQL for managing different types of storage (Database).
4. Deployment of HTML using Fabric to host the application on servers.
5. Integrating Flask web application server with stored models and HTML.
6. Establishing RestAPI for handling objects in JSON format.
7. Dynamically integrating JSON API with HTML for sharing the developed web application (AirBnB).

## Running the Console
The console can be utilized in both interactive and non-interactive modes:
- **Interactive mode**: Execute `./console.py` and enter `help` to access available commands.
- **Non-interactive mode**: Execute commands directly or via a file using `echo` or `cat`.

## Supported Commands
- **Create**: Create an object
- **Show**: Display an object based on its ID
- **Destroy**: Delete an object
- **All**: Show all objects, either of one specific type or all types
- **Update**: Modify an instance based on the class name and ID
- **Quit/EOF**: Exit the console
- **Help**: Obtain descriptions of available commands

## How to Use
Initiate the console using `./console.py`, followed by entering commands as per the supported formats.

### Create
To create an object: `create <class_name>`

### Show
To display an instance: `show <class_name> <object_id>`

### Destroy
To delete an instance: `destroy <class_name> <object_id>`

### All
To list all objects: `all` or `all <class_name>`

### Update
To update an instance: `update <class_name> <object_id> <attribute_name> "<new_value>"`

### Quit
To exit the console: `quit` or EOF (End of File) command

### Help
For command information: `help <command>`

## Supported Classes
- BaseModel
- User
- State
- City
- Amenity
- Place
- Review

## Authors
- Tamunotonye Briggs - t.briggs1@alustudent.com
- Mariam Abu - 
