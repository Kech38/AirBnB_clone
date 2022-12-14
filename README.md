

# 0x00. AirBnB clone - The console

## Project Description
This is an ALX project that involves building a full web application: the AirBnB clone. The goal of the AirBnB clone project is to eventually deploy our server a simple copy of the AirBnB Website(HBnB) This  project will be completed in milestones(steps) of which each step will link to a concept. 

The Concole is the first segment of the AirBnB clone project which will cover all fundamental concepts of the higher level programming track. A command interpreter is created to manipulate data without a visual interface, like in a Shell (perfect for development and debugging)


### Using the Console
You can run the schell (in an interactive or non-interactive mode) to manipulate your models.  You can start it from running the console.py file:

```bash
   $ ./console.py
```
The following commands are supported:

####  create:
Creates a new instance of BaseModel, saves it (to the JSON file) and prints the id. Ex:

```bash
   $ create BaseModel
```
#### show:
Prints the string representation of an instance based on the class name and id. Ex:
```bash
   $ show BaseModel 1234-1234-1234.
```

#### destroy:
Deletes an instance based on the class name and id (save the change into the JSON file). Ex:
```bash
   $ destroy BaseModel 1234-1234-1234.
```

#### all:
Prints all string representation of all instances based or not on the class name. Example to show all instances
```bash
   $ all
```
Example to show all instances of BaseModel only
```bash
   $ all BaseModel
```

#### updates:
Updates an instance based on the class name and id by adding or updating attribute (save the change into the JSON file). Ex:
```bash
   $ update BaseModel 1234-1234-1234 email "aibnb@holbertonschool.com"
```
#### quit:
quit the Shell
## Running Tests

This project uses the python unittest model for automated tests. Unittests for the AirBnB_clone project are defined in the tests folder. To run the entire test suite simultaneously, execute the following command:

```bash
  $ python3 unittest -m discover tests
```
You can specify a single test file to run at a time:

```bash
python3 -m unittest tests/tespytestt_models/test_base_model.py
```

## Authors

- [@kech38](https://github.com/Kech38) - Nkechi Asuai
- [@Beardgod7](https://github.com/Beardgod7) - Nwaoke Francis
