# Invigilator Server Application

### Overview
The Invigilator Server Application is designed to facilitate administrative tasks for educational institutions. It integrates user management, database operations, and dynamic scheduling capabilities to streamline the process of managing exams, teacher assignments, and classroom allocations.

### Features
User Authentication: Support for different user roles including admin and teacher.
Database Integration: Uses MySQL to manage and query data efficiently.
Email Notifications: Leverages Nodemailer for sending out email notifications to users.
Dynamic Query Handling: Manages classroom and schedule allocations based on real-time availability and requirements.
Prerequisites
Node.js
MySQL
NPM (Node Package Manager)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourgithub/invigilator-server-app.git
cd invigilator-server-app

Install dependencies:

bash
Copy code
npm install

Setup the database:

Ensure MySQL is installed and running.
Create a database named se_project and import the necessary tables.
Update the proj_sql.js file with your MySQL user credentials.

Start the application:

bash
Copy code
node proj_sql.js
Usage
Admin Login
POST /login: Validates admin credentials and handles session management.
Teacher Login
POST /login: Checks teacher credentials against the database for authentication.
Retrieve Schedule
POST /retrieve: Fetches available resources based on specified criteria like day, periods, and year.
Contributing
Contributions to the Invigilator Server Application are welcome. Please fork the repository and submit a pull request with your features or fixes.

### License
This project is licensed under the ISC License - see the LICENSE.md file for details.
