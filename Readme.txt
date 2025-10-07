#  To-Do List Web Application

A secure and full-featured **To-Do List Web Application** built using:
- **Frontend:** React.js  
- **Backend:** Node.js + Express.js  
- **Database:** MySQL  
- **Authentication:** JWT (JSON Web Token)  
- **Password Encryption:** bcrypt  



##  Features
 User registration and login  
 Passwords hashed with bcrypt  
 JWT-based authentication  
 Add / update / delete tasks  
 Mark tasks as completed  
 Each user sees only their tasks  
 Handles unauthorized access 

###  User Authentication
- User registration with **bcrypt password hashing**
- Secure login with **JWT (JSON Web Token)**
- Role-based access (User / Admin ready)

###  Task Management
- Add new tasks with title and description  
- View your own tasks only (filtered by logged-in user)
- Update task details (title, description)
- Mark tasks as **completed**
- Delete tasks
- Automatically records **start date**, **end date**, and **status**

###  Security
- JWT token verification middleware
- Protected routes for CRUD operations
- Encrypted passwords using bcrypt

----------------Run Project-----------------

Backend Setup
Open terminal and navigate to the backend folder:
cd backend


Install dependencies:

npm install
Run the backend server:
npm start
The backend will run on the default port (e.g., http://localhost:5050).


Frontend Setup
Open terminal and navigate to the frontend folder:
cd myapp
Install dependencies:
npm install
Run the frontend:
npm start


The frontend will open in your browser (default: http://localhost:3000).



Author
Vaishnavi Warad
Full Stack Developer | React.js | Node.js | MySQL
Email: vaishnaviwarad21@gmail.com


