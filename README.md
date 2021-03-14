<img src="https://i.pinimg.com/originals/f0/fa/45/f0fa452ce5ec464e6f6539b36d308b82.jpg">

# IPL PREDICTION

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 
[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/) 
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
<code><img height="30" src="https://github.com/tomchen/stack-icons/raw/master/logos/bootstrap.svg"></code>
<code><img height="30" src="https://symbols.getvecta.com/stencil_80/56_flask.3a79b5a056.jpg"></code>

### Contributor
<a href="https://github.com/argho28"><img src="https://avatars3.githubusercontent.com/u/54744863?s=400&v=4" height="50px" width="50px" alt=""/></a>



### Code Requirements
> Flask==1.1.1</br>
> gunicorn==19.9.0</br>
> itsdangerous==1.1.0</br>
> Jinja2==2.10.1</br>
> MarkupSafe==1.1.1</br>
> Werkzeug==0.15.5</br>
> numpy>=1.9.2</br>
> scipy>=0.15.1</br>
> scikit-learn>=0.18</br>
> matplotlib>=1.4.3</br>
> pandas>=0.19</br>

### System Requirements
> Os supported: Ubuntu 18.04.5 LTS, windows 10, windows 8</br>
> Ram: 4GB</br>
> Space: 205.9 kB</br>
> Graphics Card:2GB (minimum)</br>

### Install Packages
> pip install -r requirements.txt

### Testing
- [x]  Modules tested unit by unit
- [x]  Checked on different OS
- [x]  Thread safe supports multiprocessing

### To run the model:
> python app.py

### Hosted on web by using Heroku platform click on the link to see it:
> https://mrinmoy-ipl-prediction.herokuapp.com/

### Screenshots

### Basic UI
<img src="https://github.com/Mrinmoy-Aus/IPL_PREDICTION/blob/main/ui.png">

### 1. Open a file:
> In this module we have to open one existing file in which the Create,Read and Delete operations will be done.
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/open.png">

### 2. Initialize:
> In this module we can save a new file or if not specified it will be stored in the default project directory.
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/save.png">

### How it works? See:)
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/output.gif">

### 3. Create:
> In this module an user can insert key value pair in the database.The key is a string capped at 32chars and value is a json object capped at 16kb.The system throws proper error message for duplicate keys also.This module also supports time-to-live property if specified it will retain for the said time in the data store or else it will assume it to be infinite time if not specified.
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/create.png">
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/duplicate_error.png">

### 4. Read:
> In this module an user have to specify the key for which the respective json object will be extracted from the database and displayed in the value field.The system throws proper error message if the key is not present in the data store.This module also supports time-to-live property and does not allow read operations if the record has expired and proper messages are also generated for the said property. 
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/read.png">
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/read_error.png">
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/time-to-live.png">

### 5. Delete:
> In this module an user have to specify the key for which the respective value has to be deleted.The system throws proper error message if the key is not present in the data store.This module also supports time-to-live property and does not allow delete operations if the record has expired and proper messages are also generated for the said property.
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/delete.png">
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/delete_error.png">
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/time-to-live.png">

### 6. Show:
> This module extracts all the information from the database and makes it visible in a tabular format to the user.This module also supports time-to-live property and does not retain the records whose specified time limit has expired.
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/show.png">

### 7.	Clear:
> This module clears all the data present in Key,Value and Time-to-live input fields respectively.
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/clear.gif">
