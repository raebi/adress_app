# create a project on github and clone it to local
https://towardsdatascience.com/getting-started-with-git-and-github-6fcd0f2d4ac6

# Make a first change local and commit it to github
 - fatal: coult not read Username --> no SSH key is
   - add SSH Keys (id_rsa.pub)
 https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account
 - In Atom it is possible to add a GitHub token --> go down to left corner and click GitHub --> create token

# installl python3, pip3 and virtualenv
https://www.techiediaries.com/ubuntu/install-python-3-pip-venv-ubuntu-20-04-19/
$ sudo apt install python3-pip
$ sudo apt install python3-venv

# create a venv
in den projekt ordner wechseln
$ python3 -m venv env
aktivieren der Virtual Environment
$ source env/bin/activate

(env) <computername>:~/Development/flaskapp/adress_app (master)$

# create a flask app with cookiecutter template
 - pip install flask
 - pip install flask_SQLAlchemy
 - pip install pandas
 - pip install Flask-Bootstrap

# Project init with cookiecutter
```python3
pip3 install cookiecutter

cookiecutter https://github.com/cookiecutter-flask/cookiecutter-flask.git
```
--> wird nicht verwendet, da eine riesen app erstellt wird

Eine alternative für pypy bietet das nachfolgende cookiecutter template
```python
cookiecutter https://github.com/audreyr/cookiecutter-pypackage.git

```
