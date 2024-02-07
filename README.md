Person class will have 
fields:
id (int) - the unique user ID
firstName (String) - first name
lastName (String) -  last name
email (String) - email/username
password (String) - password

getter & setter:
firstName,lastName,email,password.

getter:
id(no setter)

Person class might also have the following :
PersonProfile - a class to gather up all of the profile information about the user
List<Events> eventsAttending - to store events the user wants to attend
List<Events> eventsOwned - a different list, to store the events the user has created

Relationship:
Person would have a many-to-many relationship with Event via List<Events> eventsAttending.
It would have a one-to-many relationship with Event via List<Events> eventsOwned.
