# LearnX Edtech Platform

LearnX is a cutting-edge EdTech platform designed to provide seamless online education. It enables students to access courses, interact with teachers, and explore learning opportunities in a modern, user-friendly environment. Built with scalability and efficiency in mind, LearnX integrates a robust backend, a dynamic frontend, and a powerful database to deliver a seamless experience.

## Features

- **User Management**: 
  - Signup/Login for Students and Teachers.
  - User profile management with dynamic dashboards.

- **Courses**:
  - Search, browse, and enroll in courses.
  - Organized course categories for easy navigation.

- **Teacher Dashboard**:
  - Tools for creating and managing courses.
  - Analytics for tracking student progress and engagement.

- **Interactive Learning**:
  - Video player with comments section.
  - Assignment submission and grading.

- **Dynamic UI**:
  - Dark mode and light mode toggle.
  - Responsive design for mobile, tablet, and desktop.

## Tech Stack

### Frontend
- **React.js**: Dynamic and reusable components.
- **Tailwind CSS**: Modern utility-first CSS framework.
- **Axios**: API integration.

### Backend
- **Node.js**: Efficient server-side JavaScript.
- **Express.js**: Lightweight web framework.
- **JWT Authentication**: Secure user authentication.

### Database
- **MongoDB**: Flexible and scalable NoSQL database.

### Other Tools
- **LocalStorage**: For theme persistence and user preferences.
- **Git/GitHub**: Version control and project hosting.

## Project Structure
```
LearnX-Edtech-Platform/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── utils/
│   │   ├── App.js
│   │   └── index.js
│   └── public/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   └── config/
├── .gitignore
├── package.json
└── README.md
```

## Installation

### Prerequisites
Ensure you have the following installed:
- Node.js
- MongoDB
- Git

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Sumitvishwakarma285/Learnx-Edtech-Platform.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Learnx-Edtech-Platform
   ```

3. Install dependencies for both frontend and backend:
   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

4. Configure environment variables:
   - Create a `.env` file in the `backend` directory.
   - Add the following variables:
     ```env
     MONGO_URI=<your-mongodb-connection-string>
     JWT_SECRET=<your-secret-key>
     PORT=5000
     ```

5. Start the development servers:
   - Backend:
     ```bash
     npm run dev
     ```
   - Frontend:
     ```bash
     cd ../frontend
     npm start
     ```

6. Access the application:
   - Frontend: `http://localhost:3000`
   - Backend API: `http://localhost:5000`

## Contributions

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- Inspiration for creating LearnX came from the vision to make learning accessible to everyone.
- Thanks to the contributors and community support.

---

### Connect
For queries or collaboration, feel free to reach out via GitHub or email.

Enjoy building with LearnX! 🚀
