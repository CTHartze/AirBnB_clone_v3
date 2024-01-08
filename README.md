# AirBnB Clone
The Airbnb clone project, which we are currently developing, involves creating a copy of the [Airbnb](https://www.airbnb.com/) platform. Only certain features will be implemented, and they will be listed below once the development is completed. At this stage, we are working on an additional storage option. Depending on the chosen database (file storage or database storage), JSON is used or MySQL, and SQLAlchemy is utilized via Python. Fabric is used for application deployment.

#### Functionalities of this command interpreter:
* Creates a new object (ex: a new User or Place)
* Retrieves object from a file, a database etc...
* Performs operations on objects (count, compute stats, etc...)
* Updates object attributes
* Destroy an object

## Table of Contents
* [Environment](#environment)
* [Installation](#installation)
* [Commands](#commands)
* [Resources](#resources)
* [Authors](#authors)
* [License](#license)

## Environment
This project is interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.4.3)
All your tests should be executed by using this command: ```python3 -m unittest discover tests```

## Installation
* Clone this repository: `git clone "https://github.com/CTHartze/AirBnB_clone_v3.git"`
* Access AirBnb directory: `cd AirBnB_clone_v3`
* Run hbnb(interactively): `./console` and enter command
* Run hbnb(non-interactively): `echo "<command>" | ./console.py`

Classes inherited from Base Model:
* [amenity.py](/models/amenity.py)
* [city.py](/models/city.py)
* [place.py](/models/place.py)
* [review.py](/models/review.py)
* [state.py](/models/state.py)
* [user.py](/models/user.py)

## Commands

Commands | Description | Utilization
-------- | ----------- |-------- |
**EOF**      | . Usets console when files are passed into the program. | N/A
**quit**     | Exits console. | **quit**
**help** or **?**| Displays documented commands. | **help**
**create**  | Creates a new instance of the \<class_name\>, saves it (to the JSON file) and prints the id. | **create** \<class_name\>
**destroy** | Deletes an instance base on the class name and id(saves the change into the JSON file). | **destroy** \<class_name class_id\>
**show**    | Prints the string representation of an instance based on the class name and id. | **show** \<class_name class_id\>
**all** | Prints all string representation of all instances based or not on the class name. | **all** or **all** \<class_name class_id\>
**update** | Updates an instance based on the class name and id by adding or updating attribute(saves the change into the JSON file). | **update** \<class_name class_id key value\>

## Authors
Alexa Orrico - [Github](https://github.com/alexaorrico) / [Twitter](https://twitter.com/alexa_orrico)  
Jennifer Huang - [Github](https://github.com/jhuang10123) / [Twitter](https://twitter.com/earthtojhuang)
Cayden Hartze [Github](https://github.com/CTHartze) / [Twitter](https://twitter.com/caydenhartze)

## License
Public Domain. No copyright protection. 
