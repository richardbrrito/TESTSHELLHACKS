# HOW-TO-SETUP-GUIDE
- SEGMENTS
    - Flask application
    - React application
    
## Flask Application

### Project Description

This is a Flask-based web application that provides various endpoints to manage users. The application supports adding, retrieving, and deleting users using HTTP methods like `POST`, `GET`, and `DELETE`.

### Features

- **Add Users**: Add a new user via a `POST` request. ENDPOINT:`/api/addUser`
- **Get Users**: Retrieve all users via a `GET` request. ENDPOINT:`/api/getAllUsers`
- **Delete Users**: Delete a user by their name via a `DELETE` request. ENDPOINT:`/api/deleteUser/`

### Installation
- **GET INTO THE RIGHT DIRECTORY** Change directories into ./server
- **CREATE A VENV** *MAC* python3 -m venv .venv | *WINDOWS* python -m venv .venv
- **ACTIVATE THE VENV** *MAC* source .venv/bin/activate | *WINDOWS* .venv\Scripts\activate
- **INSTALL REQUIREMENTS FOR VENV** *MAC* pip install -r requirements.txt | *WINDOWS* pip install -r requirements.txt


#### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Flask (`pip install flask`)

#### Setup