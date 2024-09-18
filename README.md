# The most famous AirBnB  - ON CONSOLE 

# Description of the project

This project is a clone of the most famous AirBnB website. The first stage consists of a backend interface or console to manage program data(like shell). with Console commands allow users to create, update, delete objects, and manage file storage. 

# The console - tasks
-  Put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of  future instances <br>
-  Create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
-  Create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
-  Create the first abstracted storage engine of the project: File storage.
-  Create all unittests to validate all our classes and storage engine


# Description of the command interpreter

The command interpreter helps us to manage the objects of our project by:

- Creating a new object (ex: a new User or a new Place)
- Retrieving an object from a file, a database etc…
- Doing operations on objects (count, compute stats, etc…)
- Updating attributes of an object
- Deleteing an object

## How to start the interpreter

```bash
./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  all  create  delete  destroy  exit  help  q  quit  show  update

(hbnb) 
(hbnb) 
(hbnb) quit

```

## How to use the interpreter

## Tests
To run all the tests execute the following command:

```bash
$ python3 -m unittest discover tests
```
You can also run a single test by specifying the test file:

```bash
$ python3 -m unittest tests/test_models/test_city.py

```


# Authors

## [`Fadhlullah Abdulazeez`](f.abdulazee@alustudent.com)
## [`Best Verie Iradukunda`](b.iradukund2@alustudent.com)
