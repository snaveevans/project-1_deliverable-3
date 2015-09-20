# Project 1
## Deliverable 3: Object-Oriented Version

### Project 1 High-Level Requirements

Using the previous deliverables convert existing web service code from a functional programming format to object-oriented.  This deliverable must have at least controllers and models.  Models must contain the business logic and the code that manages the persistent storage.  Persistent storage for this deliverable will implemented using MySQL 5.x.

Project 1 is a a RESTful Web Service that client(s) can create, read, update, delete or list notes.  A single note must contain four fields a name, body, username and tag(s).

It also has an endpoint to create, update, delete a user.  A user object has a 
username, password (does not need to be hashed) and full name attributes.  The name, body, tag(s), username, password and full name are just plain text.  

The RESTful API does NOT require SSL or any type of authentication to be used.  The RESTful API does NOT require any type of persistent storage, meaning everything can be in memory (RAM).  In other words use PHP arrays for in-memory storage.  Follow the currently accepted standards concerning RESTful API's as discussed in class.

This assignment will be turned via pull-requests on the Github class site.
