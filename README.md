# Tracker-Mate
> A web application used to track and control the inmates of the jail.
## Features

- ### Facial Recognition
> Used to recognize which prisoner is going for unique identification and allowing them to login into the system succesfully for further verificaation.
- ### Gesture Recognition
> Used to detect the number of fingers which will be used by the prisoners to select the destination in order to avoid contact with the system due to this COVID-19 Pandemic.
- ### Emotion Recognition
> Used to find out the agitaion in the face if he does anything wrong. 

## Running the project.
> To run this project, enter the following commands.
1. First, clone this repository
2. ```cd Oxford-Tracker-Mate```
3. Create a python virtual environment
  ```
  pip install virtualenv
  virtualenv env
  env\Scripts\activate
  ```
4. Then install all the requirements 
``` pip install -r requirements.txt```
5. Set up the Flask app
  ``` set FLASK_APP=app.py ```
6. Run the flask app
  ``` flask run ```
