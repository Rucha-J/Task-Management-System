
# Task Management System

A web-based task management system to help individuals and teams organize, track, and manage tasks efficiently. The system allows users to create, assign, and track tasks, along with setting deadlines and priorities.

## Features

- **User Authentication**: Secure login and registration for users.
- **Task Creation**: Create tasks with titles, descriptions, and deadlines.
- **Task Assignment**: Assign tasks to specific users or teams.
- **Task Status Tracking**: Mark tasks as pending, in-progress, or completed.
- **Priority Levels**: Set priority levels for each task (Low, Medium, High).
- **Search and Filter**: Search and filter tasks by status, priority, or deadline.
- **Notifications**: Get notified about upcoming deadlines or updates on tasks.
- **Role Management**: Admin can manage users and their roles within the system.
- **Task History**: Track the history of changes made to each task.
  
## Technologies Used

- **Frontend**: React.js, HTML, CSS, JavaScript
- **Backend**: Java, Spring Boot, Spring Security
- **Database**: MySQL or PostgreSQL
- **Authentication**: JWT (JSON Web Tokens)
- **Other Libraries**: Spring Data JPA, Lombok, Thymeleaf (optional for frontend)

## Installation

### Clone the repository:

```bash
git clone https://github.com/Rucha-J/Task-Management-System.git
```

### Backend Setup:

1. Navigate to the `backend` folder:

```bash
cd backend
```

2. Install dependencies using Maven:

```bash
mvn install
```

3. Create a `.env` file and configure the necessary environment variables such as database connection details and JWT secret.

4. Start the Spring Boot backend server:

```bash
mvn spring-boot:run
```

### Frontend Setup:

1. Navigate to the `frontend` folder:

```bash
cd frontend
```

2. Install dependencies:

```bash
npm install
```

3. Start the frontend development server:

```bash
npm start
```

## Usage

1. Open your browser and go to `http://localhost:3000` for the frontend.
2. Register a new user or log in with existing credentials.
3. Once logged in, you can create and assign tasks, update their status, and view your task dashboard.
4. Admins can manage users and view all tasks.

## Contributing

We welcome contributions to improve the functionality and features of the system.

### Steps to Contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add feature'`).
4. Push your changes to the branch (`git push origin feature-branch`).
5. Open a pull request with a description of the changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Spring Boot](https://spring.io/projects/spring-boot)
- [React.js](https://reactjs.org/)
- [MySQL](https://www.mysql.com/)
- [JWT](https://jwt.io/)

This `README.md` provides a structured introduction to the Task Management System project, including features, setup instructions, and contribution guidelines. Let me know if you want any changes or additions!
