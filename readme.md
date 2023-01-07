GitHub App Visualiser

Can be accesssed by the link: https://sweng-visualisation.herokuapp.com/

Able to search for GitHub users who have been authorised e.g. KennethHarmon and kvnkarthik02


To do it manually:
Install virtualenv by:
```pip install virtualenv```

Create a virtualenv:
```virtualenv env```

To start virtual environment for Windows, 
```env\Scripts\activate```  

For Mac and Linux, I think: 
```source env\bin\activate```

If anyone installs any new dependencies, run this command and commit the changes: 
```pip freeze > requirements.txt ```

To install dependencies from requirements.txt file, :
```pip install -r requirements.txt```

To run the server do one of the following
```run server/app.py```

For some this tells you flask module not found, instead try one of the two:
```python -m flask run```
```python3 -m flask run```

To run the server
```python3 server/app.py```


