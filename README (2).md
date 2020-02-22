# PayNotes

This is a NodeJS application to provide REST APIs for a note taking application.
The application is prototyped using ReactJS.

# Application flow:

Register --> Login --> Display Notes Page --> Create new Note --> Click Note to Edit --> Save Note

# Application Features:

The application would allow logged in users jot down notes.

1. POST /register
	Allows users to register on the platform with basic information Username, password, firstname, lastname

2. POST /login
 	Should authenticate and log in user

3. GET /
	Returns all notes created by the logged in user
	 
4. POST /createNote
	Allows user to create a new Note
	
5. PUT /saveEditedNote
	Allows users to edit and save an existing note

# Version
1.0.0

# Usage
A Hosted Version is on - 

# Installation

```sh
$ npm install
```

```sh
$ npm start
```