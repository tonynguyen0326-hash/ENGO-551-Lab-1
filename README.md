# Project 1

ENGO 551

This project has the basic build for a book review website, currently having a home page, registration page, login page, logout page, a page for searching for a book with its IBSN, author, title, or year, a page for each book giving information about the book, and an error page for if the book page does not exist.

create.sql: creation of tables in SQL
import.py: how the books were imported from the books.csv file using SQL
application.py: @app.route functions for how the different urls work

within templates:
layout.html: basic layout for each .html page
index.html: layout for home page
register.html: layout for registration page
login.html: layout for login page
logout.html: layout for logout page
search.html: layout for search page
book.html: layout for each page of books
error.html: layout for if an invalid ISBN is put in the url for books