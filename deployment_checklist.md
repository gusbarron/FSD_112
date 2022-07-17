# to deploy our project

1. Update the allowed hosts in settings.py
2. Install and configure whitenoise
3. Install gunicorn
3.1 update requirements.txt via `pip3 freeze > requirements.txt`
4. add a procfile with instructions for a web app. 
5. add a gitignore file with at least the following folders
5.1 venv
5.2 `*__pycache__*`
5.3 staticfiles
6. make sure to initialize a git repository and generate at least one valid commit
6.1 (Optional) Rename your main baranch to `main` via `git branch -M main`.
7. create a new heroku app via heroku create
8. push to heroku via `git push heroku main`