# web-development-flask
A minimal web app developed with Flask framework.

The main purpose is to introduce how to implement the essential elements in web application with Flask, including

URL Building

Authentication with Sessions

Template & Template Inheritance

Error Handling

Integrating with Bootstrap

Interaction with Database (SQLite)

Invoking static resources

For more basic knowledge of Flask, you can refer to a tutorial on Tutorialspoint.

How to Run
Step 1: Make sure you have Python

Step 2: Install the requirements: pip install -r requirements.txt

Step 3: Go to this app's directory and run python app.py

Details about This Toy App
There are three tabs in this toy app

Public: this is a page which can be accessed by anyone, no matter if the user has logged in or not.

Private: Only logged-in user can access this page. Otherwise the user will get a 401 error page.

Admin Page: This part is only open to the user who logged in as "Admin". In this tab, the administrator can manage accounts (list, delete, or add).

A few accounts were set for testing, like admin (password: admin), test (password: 123456), etc. You can also delete or add accounts after you log in as admin.

References
http://flask.pocoo.org/

https://www.tutorialspoint.com/flask/

Running the app.
Python main.py
Viewing the app
Go to http://127.0.0.1:5000

