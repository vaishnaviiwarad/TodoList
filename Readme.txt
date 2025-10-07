#  To-Do List Web Application

A secure and full-featured **To-Do List Web Application** built using:
- **Frontend:** React.js  
- **Backend:** Node.js + Express.js  
- **Database:** MySQL  
- **Authentication:** JWT (JSON Web Token)  
- **Password Encryption:** bcrypt  

---

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



### Run Project (Full Setup)

1. Start backend
      cd backend
      npm start
2. Start frontend
      cd myapp
      npm start
3. Open in browser → http://localhost:3000
4. Register → Login → Add tasks 
5.Create Database
    You already have a self-contained MySQL file named todolist.sql.
    create database named node1
    Run it in your MySQL terminal or GUI:
    mysql -u root -p < todolist.sql



Author
Vaishnavi Warad
Full Stack Developer | React.js | Node.js | MySQL
Email: vaishnaviwarad21@gmail.com

