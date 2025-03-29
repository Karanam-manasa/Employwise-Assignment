# Employwise-Assignment
EmployWise is a React-based web application that allows users to log in, view a list of users, edit user details, and delete users. It implements authentication and user management features using API requests.

# Features
### Level 1: Authentication Screen
- Login with email and password
   - *email* : eve.holt@reqres.in
   - *password* : cityslicka
- Token-based authentication
- Error handling for invalid credentials
- Redirect to Users List on successful login
### Level 2: List All Users
- Paginated list of users
- Displays user avatar, first name, and last name
- Pagination controls (Previous/Next)
- Responsive table layout
### Level 3: User Management
- Edit user details (first name, last name, avatar)
- Delete users
- Success/error notifications for operations
- Form validation
  
# Technologies Used
- *React.js* - Frontend library
- *React Router* - For navigation
- *CSS* - For styling
- *Axios* - For API requests
- *LocalStorage* - For token persistence


# Installation
Make sure you have the following installed on your system:
  - *Node.js* (>=14)
  - *install package* : npm 

# Steps to Set Up the Project
- *Clone the repository* :
    - git clone https://github.com/your-username/employwise-assignment.git
- *Navigate to the project directory* :
   - cd employwise-assignment
- *Install dependencies* :
   - npm install
- *Start the development server* :
   - npm start
The app will be available at http://localhost:3000/

# API Usage
This project uses Reqres API to simulate user authentication and management.
- *Login* : POST /api/login
- *Fetch Users* : GET /api/users?page=1
- *Edit User* : PUT /api/users/{id}
- *Delete User* : DELETE /api/users/{id}

# Project Structure
![image](https://github.com/user-attachments/assets/104427e2-482b-4eda-98f5-36dba1721d5e)
