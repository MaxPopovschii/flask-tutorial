# Flask Project with Authentication and Posting

This is a simple Flask web application that supports user registration and login functionality. After logging in, users can create and view posts. The project uses a database to store user information and posts.

## Features

- **User Registration**: New users can create an account.
- **User Login**: Existing users can log in to access additional functionality.
- **Create Posts**: Authenticated users can create posts.
- **View Posts**: All users can view posts.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python (3.6+)
- Flask (`pip install Flask`)
- SQLite (or any other database supported by SQLAlchemy)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/MaxPopovschii/flask-tutorial.git
   cd flask-tutorial

2. Install dependencies:
   pip install -r requirements.txt
   
4. Set up the database:
  flask --app flaskr init-db


### Running the Application

Run the application with:
  flask run
  flask --app flaskr run --debug
  
The application will be accessible at http://127.0.0.1:5000/.

### Usage
- Register: Create a new account via the /register route.
- Login: Log into an existing account via the /login route.
- Create Post: Once logged in, navigate to /create_post to make a new post.
- View Posts: Go to /posts to see all posts.


### Database

The app uses an SQL database (by default, SQLite) to store:
- User Information: Stored in the user table, including username and password hash.
- Posts: Stored in the post table, including post content and timestamp.

## Author

**Max Popovschii**  
A DevOps engineer with experience as a full-stack developer, passionate about programming, Linux, and building efficient, scalable solutions.

- GitHub: [MaxPopovschii](https://github.com/MaxPopovschii))
- Email: maxpopovschii@gmail.com

Feel free to reach out for collaboration or questions about the project!


