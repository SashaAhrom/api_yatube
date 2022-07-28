# api_yatube(educational project)
## Description
```
The project has the following endpoints:
- api/v1/api-token-auth/ (POST): we pass the login and password, we get the token.
- api/v1/posts/ (GET, POST): get a list of all posts or create a new post.
- api/v1/posts/{post_id}/ (GET, PUT, PATCH, DELETE): get, edit or delete a post by id.
- api/v1/groups/ (GET): get a list of all groups.
- api/v1/groups/{group_id}/ (GET): get information about a group by id.
- api/v1/posts/{post_id}/comments/ (GET, POST): get a list of
  all post comments with id=post_id or create a new one by specifying
  the id of the post we want to comment on.
- api/v1/posts/{post_id}/comments/{comment_id}/ (GET, PUT, PATCH, DELETE):
  get, edit or delete a comment by id for a post with id=post_id.
```
## Running a project in dev mode
```
- Install and activate the virtual environment
- Install dependencies from requirements.txt file
- pip install -r requirements.txt
- In the folder with the manage.py, run the command:
  python3 manage.py runserver
```
## System requirements
```
Python 3.7
Django 2.2.19
Djangorestframework 3.12.4
```
