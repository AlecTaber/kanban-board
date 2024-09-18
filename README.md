# Kanban Board
  ![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
## Description 

This Kanban board application allows users to securely log in and manage tasks on a Kanban-style board. User authentication is handled using JSON Web Tokens (JWT) to ensure secure access. The application features session management, with automatic logout after a defined period of inactivity. It is built using TypeScript, Sequelize ORM, and JWT for authentication.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Tests](#tests)
- [Contact](#contact)

## Installation

To install this application, you will need to clone down this repository to your local machine. Next, you will need to do an "npm install" to install all the needed packages and dependencies. After the packages are installed, you will need to set up a .env file with DB_HOST, DB_USER, DB_PASSWORD, and JWT_SECRET. You will then need to do an "npm run seed" and then an "npm run start" to get the application running on a local host port.

## Usage

To use this project, you will need to login with a provided suername and password you can find in the repo. Once logged in, you can manage your tasks and add or delete tasks from the kanban board. When you press the logout button, your session will end and you will need to log back in to manage your kanban board. Here is a link to the deployed website for you to checkout! https://kanban-board-28dh.onrender.com 

## Credits

This project was created by Alec Taber.

## License
  
  This project uses the MIT License. For more information, visit [license link](https://opensource.org/licenses/MIT).

## Features

1. **User Authentication**  
   - Secure login with username and password validation.
   - Authentication using JSON Web Tokens (JWT).

2. **Persistent Session Management**  
   - JWT is securely stored in the client's local storage after successful login for subsequent requests.
   - Session expiration after a defined period of inactivity, invalidating the JWT and requiring re-login.

3. **Error Handling**  
   - Displays an error message if the user enters an invalid username or password during login.

4. **Logout Functionality**  
   - JWT is removed from local storage upon logout, and users are redirected to the login page.

5. **Authorization Checks**  
   - Prevents unauthorized access by redirecting users to the login page if they attempt to access the Kanban board without authentication.

6. **Kanban Task Management**  
   - Users can interact with the Kanban board to manage tasks once logged in.

7. **Responsive User Interface**  
   - Designed with a clean and responsive interface for managing tasks efficiently.

## Tests

N/A

## Contact

- GitHub: [AlecTaber](https://github.com/AlecTaber)
- Email: [alectaber12@gmail.com](mailto:alectaber12@gmail.com)