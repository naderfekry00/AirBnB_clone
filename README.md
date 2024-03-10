## Project Description

This project is a simplified clone of Airbnb. It's a platform where users can list and book places to stay from their mobile phones or computers. The project is built using Python and includes a command interpreter for managing the application's data.

## Command Interpreter

The command interpreter is designed to manage the objects of our Airbnb clone. It's a console that allows us to perform CRUD operations: Create new objects, Retrieve data from objects, Update object's information, and Delete objects.

### How to Start

To start the command interpreter, navigate to the project directory and run the console.py file:

bash
./console.py


### How to Use

Once the console is running, you can use the following commands:

- create <class name>: Creates a new instance of <class name>.
- show <class name> <id>: Prints the string representation of an instance based on <class name> and <id>.
- destroy <class name> <id>: Deletes an instance based on <class name> and <id>.
- all <class name> or all: Shows all instances of <class name> or all instances of every class.
- update <class name> <id> <attribute name> "<attribute value>": Updates an instance based on <class name> and <id> by adding or updating an attribute.

### Examples

bash
$ ./console.py
(hbnb) create BaseModel
49faff9a-6318-451f-87b6-910505c55907
(hbnb) show BaseModel 49faff9a-6318-451f-87b6-910505c55907
[BaseModel] (49faff9a-6318-451f-87b6-910505c55907) {'id': '49faff9a-6318-451f-87b6-910505c55907', 'created_at': '2022-03-22T14:00:00', 'updated_at': '2022-03-22T14:00:00'}
(hbnb) update BaseModel 49faff9a-6318-451f-87b6-910505c55907 name "Betty"
(hbnb) show BaseModel 49faff9a-6318-451f-87b6-910505c55907
[BaseModel] (49faff9a-6318-451f-87b6-910505c55907) {'id': '49faff9a-6318-451f-87b6-910505c55907', 'created_at': '2022-03-22T14:00:00', 'updated_at': '2022-03-22T14:00:00', 'name': 'Betty'}
(hbnb) destroy BaseModel 49faff9a-6318-451f-87b6-910505c55907
(hbnb) show BaseModel 49faff9a-6318-451f-87b6-910505c55907
** no instance found **
(hbnb) quit

