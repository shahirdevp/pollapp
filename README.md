## Django Polls Application  

 ## Requirements  
  
 The application requires  
 * Django 2.0.3 or newer  
 * Python add-on modules as in [https://github.com/shahirdevp/pollapp/blob/master/pollsapi/requirements.txt](requirements.txt)
 * Vue cli 4
  
  
 ## Django Installation

### Step 1
Open the Terminal and type the following command:    
```
git clone https://github.com/shahirdevp/pollapp.git
```   
    
### Step 2     
Go to `poll` directory:    
```
cd poll
```

### Step 3
Create virtual environment.    
```
For Windows:
    python -m venv venv

For Mac/Linux:
    python3 -m venv venv
```
### Step 4
Activate virtual environment.
```
For Windows:
    venv\bin\activate.bat

For Mac/Linux:
    source venv/bin/activate
```
### Step 5
Install requirements.    
```
(venv) pip install -r requirements.txt
```
  
### Step 6
Migrate your database:  
```
(venv) python manage.py migrate
```
Make sure you have `db.sqlite3` file in `poll`  
  
 ## Running  
  
### Step 1    
Go to `poll` directory    

### Step 2   
Run following command on the Terminal    
 ```
(venv) python manage.py runserver
 ``` 
## Api Documentation

```
docs/
```
OR
```
swagger-docs/
```


