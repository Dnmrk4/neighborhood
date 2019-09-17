# Neighborhood-watch

An application that allows a user to join a neighborhood, post updates on the neighbourhood and have the emergency contacts.

#### Author

_Created by_ **Danmark Mutai**

## Technologies Used

* Python
* HTML
* Django micro-framework
* Bootstrap(used for styling)
* JavaScript


## Setup/Installation Requirements

* To start using this project use the following commands:

`git clone https://github.com/Dnmrk4/neigbourhood.git`

- Now open the text editor.

- open your terminal and navigate to neighbourhood then create a virtual environment.

* To run the app, you'll have to run the following commands:

`pip install -r requirements.txt`

- Create database instagram using the command below.

`#CREATE DATABASE watch;`

- Then migrate the database using the command below

`python3.6 manage.py migrate`

- Then run the app, so that the app will be available on localhost:8000, to do this run the command below

`python manage.py runserver`

- access the application on this localhost address http://127.0.0.1:8000

## Behaviour Driven Development

|  Behaviour |  Input  |  Output |
|------------|---------|---------|
| The program should navigate to the login page on load | On page load | Navigate to the login page |
| The program should navigate to sign up page when Sign Up is clicked | Click on Sign Up on the navigation bar | Redirected to the sign up page |
|The program should navigate to the login page when Logout is clicked on the navigation bar | The program should navigate to the login page when Logout is clicked on the navigation bar |  Redirected to the login page |
|The program should direct the user to their neighborhood page when logged in and already has a neighborhood |  sign in | Redirected to their neighborhood page |
|The program should direct the user to the index page with neighborhood listings when logged in and has no neighborhood | sign in | Redirect the user to the index page with neighborhood listings |
|The program should navigate to the profile page when the My Profile is clicked on the navigation bar | Click on My Profile on the navigation bar  | Redirected to the profile page|

## Prerequisites

* You need the following to work on the project: 

- Python version 3.6 
- Django 
- virtualenv & pip  

## Link to Live Website: https://community-watch.herokuapp.com/

## License

This application uses a [MIT license.](/LICENSE)

_Copywrite (c)_ **Danmark Mutai** _2019_
