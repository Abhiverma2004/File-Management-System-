# File-Management-System-

Project: File Management System using Node.js and Express with EJS
Project Description
This project is a simple File Management System that allows users to manage text files through a web-based interface. It provides functionalities to list, view, create, and rename files stored in a directory. The system is built using Node.js and Express.js for backend operations, while EJS (Embedded JavaScript) is used for rendering dynamic views.

Features of the Project
List Files – Displays a list of all files stored in the /files directory.
View File Content – Users can open and read the content of a selected file.
Create a New File – Users can create new text files by entering a title and content.
Rename a File – Users can rename existing files.
Static File Support – Public files such as stylesheets and scripts can be served.
Technologies Used
Backend:
Node.js – JavaScript runtime for server-side operations.
Express.js – Web framework for handling HTTP requests and responses.
File System (fs) Module – Used to read, write, rename, and manage files.
Path Module – Helps in managing file and directory paths.
Frontend:
EJS (Embedded JavaScript) – Templating engine to render dynamic web pages.
HTML, CSS – Basic structure and styling for the interface.
Other Dependencies:
express.json() – Middleware for handling JSON requests.
express.urlencoded() – Middleware for handling form data.
Static Files – The project serves static files using express.static().
How the Project Works?
User visits the homepage (/) → A list of available files is displayed.
User clicks on a file → The file content is rendered on the page.
User creates a new file → The file is saved in the /files directory.
User renames a file → The file's name is changed in the directory.
All operations are reflected dynamically using EJS templates.
Possible Enhancements
Add a delete file feature.
Implement authentication for secure access.
Support file uploads for different formats.
Use a database for file metadata management.
