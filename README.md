# Task-Master
This Flask application is a simulated task manager that allows users to create, view, update, and delete tasks. It's designed as a learning tool to demonstrate the fundamentals of Flask web development. By building this app, you'll gain experience with:

Routing: Defining different URLs for specific actions in your application.<br>
Templating: Using HTML templates to structure and display content in your web pages.<br>
Forms: Creating forms to capture user input for adding or updating tasks.<br>
Databases: Interacting with a database (SQLite in this case) to store and manage task data.<br>
This basic task manager provides a foundation for understanding how Flask applications are structured and how they interact with users.

## Running the Flask App

**Prerequisites**

* Python 3.6 or later ([https://www.python.org/downloads/](https://www.python.org/downloads/))
* pip (usually comes bundled with Python)

**Installation**

1.  Clone the repository using Git:

    ```bash
    git clone https://github.com/JashT14/Task-Master.git
    ```


2.  Navigate to the project directory:

    ```bash
    cd Task-Master
    ```

3.  Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

**Running the App**

1.  Start the development server:

    ```bash
    python app.py
    ```

    This will typically start the Flask development server on `http://127.0.0.1:5000/` by default. You can access the application in your web browser at that URL.

**Additional Notes**

* The `requirements.txt` file lists all the Python packages required by the application.
* The `app.py` script is a common way to start Flask applications in development mode.

**Development Tips**

* Flask applications typically use a web development framework like Jinja2 for templating. You may want to familiarize yourself with Jinja2 syntax if you plan to modify the application's templates.
* By default, the Flask development server is not recommended for production use. Consider using a production-ready web server like Gunicorn or uWSGI when deploying your application to a live server. 

For more information about Flask development, refer to the official Flask documentation: [https://flask.palletsprojects.com/](https://flask.palletsprojects.com/)
