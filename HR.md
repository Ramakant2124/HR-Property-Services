python3 -m venv env
Set-ExecutionPolicy Unrestricted -Scope Process
env\scripts\activate
$env:FLASK_APP = "main"
flask run