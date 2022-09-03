
0x00. AirBnB clone - The console
Project Description
This is an ALX project that involves building a full web application: the AirBnB clone. The goal of the AirBnB clone project is to eventually deploy our server a simple copy of the AirBnB Website(HBnB) This project will be completed in milestones(steps) of which each step will link to a concept.

The Concole is the first segment of the AirBnB clone project which will cover all fundamental concepts of the higher level programming track. A command interpreter is created to manipulate data without a visual interface, like in a Shell (perfect for development and debugging)

Using the Console
You can run the schell (in an interactive or non-interactive mode) to manipulate your models. You can start it from running the console.py file:

   $ ./console.py
The following commands are supported:

create:
Creates a new instance of BaseModel, saves it (to the JSON file) and prints the id. Ex:

   $ create BaseModel
show:
Prints the string representation of an instance based on the class name and id. Ex:

   $ show BaseModel 1234-1234-1234.
destroy:
Deletes an instance based on the class name and id (save the change into the JSON file). Ex:

   $ destroy BaseModel 1234-1234-1234.
all:
Prints all string representation of all instances based or not on the class name. Example to show all instances

   $ all
Example to show all instances of BaseModel only

   $ all BaseModel
updates:
Updates an instance based on the class name and id by adding or updating attribute (save the change into the JSON file). Ex:

   $ update BaseModel 1234-1234-1234 email "aibnb@holbertonschool.com"
quit:
