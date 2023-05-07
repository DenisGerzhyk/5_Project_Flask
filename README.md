# 5_Project_Flask

This code is a Flask web application that manages a simple blog database. It includes the following:

Importing Flask, request, render_template, redirect, url_for, and SQLAlchemy modules, and datetime class.
Creating a Flask application and initializing it with the configuration settings for the SQLite database.
Defining a model for the blog article with fields for id, title, intro, and date.
Creating routes to handle HTTP requests and manage CRUD operations on the blog database:
a. The /add route allows adding new articles to the database and renders a form to submit a new article.
b. The /search route searches for articles in the database by title.
c. The /display route displays all articles in the database in descending order of date.
d. The /display/int:id route displays the details of a particular article.
e. The /display/int:id/delete route deletes a particular article from the database.
f. The /display/int:id/edit route edits the details of a particular article and updates the database.
The templates for the application are also included, which include HTML and Jinja2 templating syntax for rendering the data dynamically in the web pages.
