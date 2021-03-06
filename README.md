# Pitchadd
Pitchadd is an application that allows users to create pitches. The users submit their one pitches and other users will vote on them and leave comments to give their feedback.


## Author
> Dolphine Atieno

## Installations

The following command installs all the application requirements
>``pip freeze -r requirements.txt``

## Setup
Run 
``git clone https://github.com/Atienodolphine01/Pitchadd.git``

or download the zip file from github.

After extracting the files, 

1. Navigate to the project folder
>`` cd gitSearch.`` 

2. Creating a virtual environment
>``virtualenv virtual.``

3. Activating the virtual environment
>``source virtual/bin/activate.``

4. Running the application
>``python3 manage.py server``

5. Running tests

 > ``python3 manage.py test.``

## Technologies used
* Python3
* Flask
* Javascript
* Particle Js
* Html5
* Css3
* Bootstrap4

## User Stories
* As a user, I would like to see the pitches other people have posted.
* As a user, I would like to vote on the pitch they liked and give it a downvote or upvote.
* As a user, I would like to be signed in for me to leave a comment
* As a user, I would like to receive a welcoming email once I sign up.
* As a user, I would like to view the pitches I have created in my profile page.
* As a user, I would like to comment on the different pitches and leave feedback.
* As a user, I would like to submit a pitch in any category.
* As a user, I would like to view the different categories. 

## BDD(Behaviour Driven Development)
>Login Inputs

| Inputs |  Description |
| :---         |          ---: |
| Username  | Account username, ``eg Dolphine``|
| Password  | Account password, ``eg parseword``|

>Signup inputs

| Inputs |  Description |
| :---         |          ---: |
| Username  | Account username, ``eg Dolphine``|
| Email  | User email, ``eg dolphine@testmail.com``|
| Password  | Account password, ``eg parseword``|
| Confirm Password  | Account password, ``eg parseword``|

> Pitches inputs

| Inputs | Description  |
|---|---|
|  Heading | Pitch description eg; ``pickup lines``  |
|  Pitch text| The actual pitch body|
| Comment| A comment on the pitch|



## License
> MIT License &copy; 2020 AtyenoD

## Collaborate
To collaborate, reach me on [awuordolphine65@gmail.com]()
