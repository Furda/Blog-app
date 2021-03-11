# Blog Web App

* Users can create and delete blog posts
* Users can create an account
* Users must log in to create blog posts, drafts, and comments
* Superusers can approve and delete comments in blog posts
* Markdown and syntax highlighting enable

## Working app

 https://blog-dj-app.herokuapp.com/

## Initial Setup Instructions

### Setup Python Virtual Environment

```buildoutcfg
python3 -m venv venv
. venv/bin/activate
pip3 install -r requirements.txt
```
## Running Server

```buildoutcfg
./mange.py migrate
./mange.py runserver
```
### Go and check `http://127.0.0.1:8000/`

## Built With

* [Python](https://www.python.org) - Language
* [Django](https://www.djangoproject.com) - Web framework
* [pip](https://pypi.org/project/pip/) - Dependency Management

## Acknowledgments

* This API was built following the Profitable Programmer course 
* You can visit the course page here: https://course.profitableprogrammer.co/pp-2019
