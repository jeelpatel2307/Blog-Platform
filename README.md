# Blog Platform with Flask

This project is a simple Blog Platform built using the Flask web framework in Python. Users can register, log in, create blog posts, and view existing posts.

## Project Structure

### 1. `blog_platform.py`

- Contains the main code for the Blog Platform.
- Utilizes Flask for web development and SQLAlchemy for database operations.
- Defines two models: `User` for user information and `Post` for blog posts.
- Implements routes for home, user registration, login, logout, and creating new posts.

### 2. `templates/`

- Contains HTML templates for rendering web pages:
    - `home.html`: Displays all blog posts.
    - `register.html`: Allows users to register.
    - `login.html`: Handles user login.
    - `new_post.html`: Allows users to create new blog posts.

## How to Run

1. Save the code in a file named `blog_platform.py`.
2. Install required packages: `pip install flask flask_sqlalchemy`.
3. Run the program using the command:
    
    ```bash
    python blog_platform.py
    
    ```
    

## Usage

1. Access the home page at `http://127.0.0.1:5000/` to view existing blog posts.
2. Register a new account by visiting `http://127.0.0.1:5000/register`.
3. Log in using your credentials at `http://127.0.0.1:5000/login`.
4. Create a new blog post at `http://127.0.0.1:5000/new_post`.

## Customization

Feel free to customize and expand upon this project based on your requirements. Possible enhancements include adding user authentication, post categories, comments, and improving the user interface.

## Author

Jeel patel
