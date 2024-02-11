#AirBnB clone
- . The goal of the project is to deploy on your server a simple copy of the AirBnB website.
- .This project is a web application composed by:
- . A command interpreter to manipulate data without a visual interface, like in a Shell (perfect for development and debugging)
- . A website (the front-end) that shows the final product to everybody: static and dynamic
- . A database or files that store data (data = objects)
- . An API that has a communication interface between the front-end and your data (retrieve, create, delete, update them)
- . This project application will not be built all at once, but step by step:

#(Step 1) The console:

- overwrites default emptyline method and does nothingcreate your data model
- Retrieve an object from a file, a database etc...
- operations on objects (count and compute stats.)
- Update attributes of an object
- Destroy an object

#Table of Content

- Environment
- Installation
- File descriptions
- Usage
- Examples of use
- Bugs
- Authors
- License

#Environment

- This project is interpreted/tested on Ubuntu 14.04 LTS using python3 (version 3.4.3)

# Installation
- Clone this repository: git clone ``"https://github.com/bryansine/AirBnB_clone.git"``
- Access AirBnb directory: ``cd AirBnB_clone``
- Run hbnb(interactively): ``./console and enter command``
- Run hbnb(non-interactively): ``echo "<command>" | ./console.py``

#File dsecriptions
- console.py - the console contains the entry point of the command interpreter. List of commands this console current supports:
- `EOF` - exits console
- `quit` exits console
- `<emptyline`> -  overwrites default emptyline method and does nothing
- `]create` - Creates a new instance ofBaseModel, saves it (to the JSON file) and prints the id
- `destroy` - Deletes an instance based on the class name and id (save the change into the JSON file).
- show - Prints the string representation of an instance based on the class name and id.
-`all` - Prints all string representation of all instances based or not on the class name.
- `update` - Updates an instance based on the class name and id by adding or updating attribute (save the change into the JSON file).


# Testing
 This project uses python library, unittest to run tests on all python files.
- interactive test

- `python3 -m unittest discover tests`
- Non interactive
- `echo "python3 -m unittest discover tests" | bash`

###exampls of some of the available commads:

- show
- create
- update
- destroy
- count

##How to use it
 in interactive mood

$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$


in Non-Intearctive mood

$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$


##Bugs
No Known Bugs at this time

##Author
Bryan sine

##liicense
Public Domain. No copy write protection

