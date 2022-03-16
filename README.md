# MyProjects

## Author  
  
[Github](https://github.com/faisoabdirisak)

# Description  
The application will allow a user to post a project he/she has created and get it reviewed by other users.

##  Live Link
 Click [View Site]()  to visit the site.

  ## Screenshots
###### Profiles
<img src="">
 

###### project
<img src="">

###### Accounts
<img src="">


## User Story  

* View posted projects and their details
* Post a project to be rated/reviewed
* Rate/ review other users' projects
* Search for projects
* View projects overall score
* View my profile page

## Setup and Installation  

To get the project .......  
  
##### Cloning the repository:  
 ``` 
git clone https://github.com/faisoabdirisak/MyProjects.git
```
##### Navigate into the folder 
 ``` 
cd MyProjects
```
##### Install and activate Virtual  
 ``` 
- python3 -m venv virtual - source virtual/bin/activate  
```  
##### Install Dependencies  
 ``` 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ``` 
python manage.py makemigrations 
 ``` 
 Now Migrate  
 ```
 python manage.py migrate 
```
##### Run the application  
 ``` 
 python manage.py runserver 
``` 
##### Running the application  
 ``` 
 python manage.py server 
```
##### Testing the application  
 ``` 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  


## How the app works
A user needs to log in if they have na existing account
A user can sign up f they do not have an account
A user then can be able to view a persons profile and the projects they have posted.