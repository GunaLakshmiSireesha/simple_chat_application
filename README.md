##Simple PHP Chat Application
   This is a basic chat application built using PHP, HTML, CSS, and MySQL. It allows users to register, log in,
   and participate in a chat.

## Features
  - User Registration: New users can create an account with a name, email, password, and an profile image.
  - User Login: Registered users can log in using their email and password.
  - Session Management: The application uses PHP sessions to maintain user login state.
  - Image Upload: Users can upload a profile picture during registration.
  - 
#Database Setup:
 -Create a database named db_chat.
 -Create a user table with the following columns: id, name, email, password, image.
 -Create a message table with following columns: id, name, email,  image ,message,time.

#Configuration:
-Update the conn.php file with your database credentials.

#Run the Application:
 -Place the project files in your web server's root directory.
 -Open your browser and navigate to http://localhost/login.php (or the appropriate URL for your setup).

#Project Structure
 *login.php: Handles user login and redirects to the chat page upon successful login.
 *registration.php: Manages user registration and image uploads.
 *chat.php: The main chat interface (not provided in the code, but the destination of the login).
 *conn.php: Contains the database connection details.
 *image/: Directory to store uploaded user profile pictures.
