# Forum Web Application

This is a web forum project that allows users to communicate with each other, post and comment on topics, like/dislike posts and comments, and filter posts based on categories and user interactions.

## Getting Started

To run this web forum application, follow these steps:

1. Clone this repository to your local machine and navigate to the project directory:
-
   ```bash 
   git clone: https://github.com/JBL08/forum.
  ```
-
   ```bash
    cd forum
    ```

2. Open Visual Studio Code (VS Code):
-
   code .
   ```

3. In VS Code, open the integrated terminal (usually at the bottom of the window).
4. Run the following command to start the application:
 ```bash
 go run data.go
 ```

## Features
User Authentication
Users can register as new users by providing their email, username, and password.
Passwords are securely stored with encryption (Bonus feature).
The forum checks if the email is already registered and validates user credentials.

## Communication
Registered users can create posts and comments.
Posts can be associated with one or more categories.
All posts and comments are visible to all users, registered or not.

## Likes and Dislikes
Registered users can like or dislike posts and comments.
The number of likes and dislikes is visible to all users.

## Filtering
Users can filter posts by categories, created posts, and liked posts.
Categories act as subforums, allowing users to focus on specific topics.
Filtering by created and liked posts is available for registered users and is specific to the logged-in user.

## Technologies Used
SQLite: Used for data storage, including users, posts, comments, and more.
Go: The backend of the web application is written in Go (Golang).
Docker: Containerization technology to ensure consistent deployment.
HTML: Used for building the web pages.
HTTP: Used for communication between the client and server.
Sessions and Cookies: Used to manage user sessions.
bcrypt: Used for password encryption.
UUID: Optional usage for enhancing session security (Bonus task).

## Project Requirements
Use SQLite for data storage.
Implement user registration and authentication.
Enable users to create posts and comments.
Allow liking and disliking of posts and comments.
Implement filtering of posts by categories, created posts, and liked posts.
Use Docker for containerization.
Handle website errors and HTTP status codes.
Handle technical errors gracefully.
Adhere to coding best practices.
Recommended: Include unit tests.

## Allowed Packages
All standard Go packages.
sqlite3
bcrypt
UUID

## Project Restrictions
Do not use any frontend libraries or frameworks like React, Angular, or Vue.

## Author
Juhena B

## Acknowledgments
This project was created as part of a 01 Founders learning experience to gain practical knowledge in web development, Docker, SQL, and encryption.

