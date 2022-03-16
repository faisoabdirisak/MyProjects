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

## Technology used  
  
* python3.8  
* Django 4.1
* Html
* CSS
* Javascript
* Heroku

## Known Bugs  
* There are no known bugs 
  
## Licence

MIT License    [MIT](https://choosealicense.com/licenses/mit/)


Copyright (c) [2022] [Faiso Abdirisak]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.