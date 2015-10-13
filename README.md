# Project 1
## Deliverable 3: Object-Oriented Version

### Project 1 High-Level Requirements

Build an *object-oriented* version of a ReSTful Web Service using PHP 5.x.  Follow the *[domain-driven design or onion architecture](http://blog.8thlight.com/uncle-bob/2012/08/13/the-clean-architecture.html)*.  Persistent storage for this deliverable will implemented using *MySQL 5.x* only.  The web service does **NOT** require *SSL* or any *authentication* to be consumed. 

The RESTful Web Service will provide client(s) the ability to create, read, update, delete or list notes.  A single note contains a unique identifier, title, body, owner username and tag(s).  When getting a list of notes the client(s) should be able to select notes based on a tag or owner username.  The client(s) should be able to sort the results of the list in either ascending or descending order.

The RESTful Web Service will provide client(s) the ability to create, read, update, delete or list users.  The user information required is first and last name, unique username, password (at least 8, no more than 15, alpha-numeric characters with at least one special character), created timestamp, last login timestamp, last updated timestamp and what groups they belong to.  There are only *two* groups as this time *admin* and *user*.  Timestamps should be stored as UTC.  When querying the API for a user list the client(s) should be able to sort based on last name, username, all timestamps and groups.

### Key Grading Points

- DDD/Onion directory structure
- Persistent storage that is implement agnostic
- Requests/responses adhere to HATEOS
- Data is sanitized
- Data is validated
- Timestamps are stored in UTC
- Passwords are not human readable in the database

This assignment will be turned via pull-requests on the Github class site.
