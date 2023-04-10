# API_programming

# Initialize virtual environment on the commmand line
Create virtual envirnoment
```
py -m venv .venv
```
Upgarde pip
```
py -m pip install --upgrade pip
```
Set permission for program
```
Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope CurrentUser
```
Install packages from requirements.txt
```
pip install -r .\requirements.txt
```
Freeze 
```
python -m pip freeze > requirements.txt
```

# Installation
Reference link: 
https://fastapi.tiangolo.com/
https://fastapi.tiangolo.com/async/#in-a-hurry

FastAPI
```
pip install fastapi
```
We need an ASGI server, for production such as Uvicorn
```
pip install "uvicorn[standard]"
```

# Commands:
Run server
```
uvicorn main:app --reload
```

# Some problems:
* Problem 1: error: httptools
Solution 1: Install full "Desktop development with C++" 

* Problem 2: Cannot access server from mobile devide
Solution 2: Run server with command: uvicorn main:app --reload --host 0.0.0.0. 
Read more: https://fastapi.tiangolo.com/zh/deployment/manually/ 


