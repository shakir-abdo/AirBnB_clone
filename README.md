### Airbnb Clone

#### Description

AirBnB is a complete web application, integrating database storage, a back-end API, and front-end interface in a clone of AirBnB.

This team project is part of the Alx Software Engineering program. </br>
It represents the first step towards building a full web application.

#### This first step consists of:
> Console part of the AirBnB clone project.
> This repository holds a command interpreter and classes (i.e. BaseModel class
> and several other classes that inherit from it: Amenity, City, State, Place,
> Review), and a command interpreter. The command interpreter, like a shell,
> can be activated, take in user input, and perform certain tasks
> to manipulate the object instances methods and attributes.

#### How to Use Command Interpreter
---
| Commands  | Sample Usage                                  | Functionality                              |
| --------- | --------------------------------------------- | ------------------------------------------ |
| `help`    | `help`                                        | displays all commands available            |
| `create`  | `create <class>`                              | creates new object (ex. a new User, Place) |
| `update`  | `User.update('123456', {'name' : 'Someone'})`  | updates attribute of an object             |
| `destroy` | `User.destroy('123456')`                         | destroys specified object                  |
| `show`    | `User.show('123456')`                            | retrieve an object from a file, a database |
| `all`     | `User.all()`                                  | display all objects in class               |
| `count`   | `User.count()`                                | returns count of objects in specified class|
| `quit`    | `quit`                                        | exits                                      |

#### Installation
```bash
git clone git@github.com:shakir-abdo/AirBnB_clone.git
cd AirBnB_clone
```
#### Usage
Interactive Mode
```bash
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$
```
Non-Interactive Mode
```bash
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
```