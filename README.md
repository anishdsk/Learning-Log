# Learning-Log

## URL:

#### My Heroku account is experiencing problems at the moment. I contacted Heroku to fix it so the URL may be down for a few days. I have uploaded images of the web-app's pages and features at the bottom of the README that you can look at in the meantime.

https://simplelearninglog.herokuapp.com/

*Load times may take a bit longer sometimes as Heroku puts the app to sleep if it has been idle for a while*

## Overview & Technical Features:
Users can log information about topics they're learning about and make detailed entries as they learn about each topic.

      - Utilized Python's Django web-framework to handle/route data between webpages and the backend/database
      - Implemented user login/registration and authentication using Django's built-ins for forms and security
      - Used SQLite to hold information about data models (Topics, Entries, Users, primary/foreign keys)
      - Each user's data (topics & entries) is saved between logins
      - Used HTML/Bootstrap to make responsive webpages
      - Administrator privileges are held by me
      - Created within a virtual environment 
      - Deployed to Heroku

## Running Locally:
      - Clone the repo into a directory
      - Make sure Python is already installed and added to PATH on your computer
      
      - Install dependencies using pip
            - "pip install django"
            - "pip install django-heroku"
            - "pip install djang-bootstrap4"
            
      - Wile in the directory and with the command line open, type in "python manage.py migrate"
      - Now type in "python manage.py runserver" while in the same directory
      - After running the above command, one of the outputted lines will have the URL
      - Copy/paste the URL into a browser and start using the web-app locally
      
## Images:
### Homepage
![](images/home_page.PNG)

### Registration Page
![](images/registration_page.PNG)

### Login Page
![](images/login_page.PNG)

### Add Topic page
![](images/add_topic.PNG)

### All Topics page
![](images/topics.PNG)

### Add Entry page
![](images/add_entry.PNG)

### All Entries page
![](images/entries.PNG)

      
