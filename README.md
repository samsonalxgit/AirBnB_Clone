AirBnB clone Project

Description about the project
First phase of AirBnB clone Project. In this phase the project team developed command line application to manage instances of AirBnB Project such as Places, Cities, Users, Amenities and Reviews that are based on class called BaseModel. The command line application can be used to create, Update, Retrive and count and remove object instance as needed.

How to start
Inorder to start the console applications use ./console.py

How to use it
help command: Help command helps user to understand each one of the commands available. List avilable commands by typing:

help

Understand a specific command by typing:

help command like help quit

create command: Create a new object:

create <object class>

So the classes that we manage are:

BaseModel
User
Amenity
City
Place
State
Review
all command: List all the created objects by typing:

all or .all()

Inorder to list all the objects of a specific class type:

all <class name> like all Userir the second way <class name>.all() like City.all()

count command: Count number of objects that belong to a specific class by typing:

count <class name> like count Place or the second way <class name>.count() like Review.count()

show command: Print the string representation of a specific objects by typing: show <class name> <id> ex: show Review 12345or the second way <class name>.show("id") like Review.show("12345").

destroy command: Deletes a specific object by typing: destroy <class name> <id> ex: destroy Review 12345or the second way <class name>.destroy("id") like Review.destroy("12345").

update command: Updates a specific object by typing:

update <class name> <id> <name> "<value>" ex: update Review 12345 name "Marco"
<class name>.update("id", "<name>", "<value>") ex: City.update("12345", "item", "bed")
<class name>.update("id", {'<name1>: "<value1>", '<name2>': "<value2>"}) ex City.update("12345", {'item1': "bed", 'item2': "bathroom"})
[Note] If the attribute of the class exists it will be replace with the new value, otherwise it will create a new attribute for the specified instance.

commands to exit the program if you want to exit the program you should type:

quit or Ctrl+D or EOF

Author
Samson Manie <samsonmanie2022gmail.com>
