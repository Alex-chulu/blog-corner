# Blogging Platform

Blogging Platform is a simple web application that allows users to create, edit, and delete their blogs. It provides a platform for users to express themselves and share their thoughts with the world.

## Features

- User Registration and Authentication: Users can create an account, log in, and manage their blogs.
- Create Blogs: Users can write and publish their blogs with a title and content.
- Edit and Delete Blogs: Users can edit or delete their existing blogs.
- Responsive Design: The web application is responsive and works well on various devices.

## Technologies Used

- Python: The backend of the application is built using Python with the Flask web framework.
- MySQL Database: User and blog data are stored in a MySQL database.
- HTML/CSS: Frontend templates and styling are created using HTML and CSS.
- Flask-WTF: For handling forms and validation.
- Flask-SQLAlchemy: For database interactions.
- Flask-Login: For user authentication and session management.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/blogging-platform.git
   cd blogging-platform

1. Create a virtual environment and activate it:
python -m venv venv
source to-do/Scripts/activate

2. Install the required packages:
3. Set up the MySQL database. Create a config.py file in the project root with the following content, replacing <your-database-connection-details> with your MySQL connection details:
SQLALCHEMY_DATABASE_URI = 'mysql://<username>:<password>@<host>/<database>'

4. Initialize the database:
flask db init
flask db migrate
flask db upgrade

5. Run the application:
flask run

6. Access the application in your web browser at http://localhost:5000.

7. Contributing
If you'd like to contribute to this project, please open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.


Please replace `<your-database-connection-details>` in step 4 with your actual MySQL database connection details.