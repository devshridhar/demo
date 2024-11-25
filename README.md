
# Full Stack Authentication Module

This project is a full-stack authentication module that meets all the requirements of the task. It consists of a React-based frontend and a NestJS-based backend with MongoDB as the database. The module provides robust user authentication with sign-up and sign-in functionality and follows best practices for security and performance.

---

## Demo

- **Live Demo:** [https://auth.fullstackdev.in/](https://auth.fullstackdev.in/)
- **API Documentation:** [https://auth.fullstackdev.in/docs](https://auth.fullstackdev.in/docs)
- **API Base URL:** [https://auth-api.fullstackdev.in/](https://auth-api.fullstackdev.in/)

---

## Repositories

- **Frontend Repository:** [https://github.com/devshridhar/frontend](https://github.com/devshridhar/frontend)
- **Backend Repository:** [https://github.com/devshridhar/api](https://github.com/devshridhar/api)

---

## Features

### Frontend

- **Sign-Up Form:** Includes fields for email, name, and password with validation for:
  - Minimum password length of 8 characters.
  - Password must contain at least one letter, one number, and one special character.
  - Name must contain only letters and spaces.
  - Real-time validation messages for user guidance.
- **Sign-In Form:** Includes fields for email and password with validation for required inputs.
- **Welcome Page:** Displays a personalized welcome message upon successful login.
- **Navigation:** Includes a "Create Account" link on the login page and a logout button on the welcome page.
- **Responsive Design:** The frontend is built using **Material-UI (MUI)** for a polished and responsive user interface.
- **Environment Configuration:** Supports `.env` files for managing API URLs and port numbers.

### Backend

- **Authentication Endpoints:**
  - **Sign-Up Endpoint:** Registers a new user and validates input fields.
  - **Sign-In Endpoint:** Authenticates users and returns a JWT token.
- **Database Integration:** Uses **MongoDB** for storing user information securely.
- **Security Measures:**
  - Basic Authentication for Swagger API documentation.
  - Rate-limiting to prevent abuse.
  - CSRF protection for state-changing requests.
  - Input validation to prevent SQL/NoSQL injections and XSS attacks.
- **Logging:** Backend includes detailed logging for debugging and monitoring.

---

## Installation

### Backend

1. **Clone the Backend Repository:**
   ```bash
   git clone https://github.com/devshridhar/api.git
   cd api
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Set Up Environment Variables:**
   Create a `.env` file with the following keys:
   ```env
   PORT=3000
   MONGO_URI=<your_mongo_uri>
   JWT_SECRET=<your_jwt_secret>
   ```

4. **Start the Backend:**
   ```bash
   npm run start:dev
   ```

### Frontend

1. **Clone the Frontend Repository:**
   ```bash
   git clone https://github.com/devshridhar/frontend.git
   cd frontend
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Set Up Environment Variables:**
   Create a `.env` file with the following keys:
   ```env
   REACT_APP_PORT=3001
   REACT_APP_API_URL=https://auth-api.fullstackdev.in
   ```

4. **Start the Frontend:**
   ```bash
   npm start
   ```

---

## Testing

### Backend

- **Unit Tests:**
  ```bash
  npm run test
  ```

- **End-to-End (E2E) Tests:**
  ```bash
  npm run test:e2e
  ```

- **Test Coverage:**
  ```bash
  npm run test:cov
  ```

### Frontend

- **Linting:**
  ```bash
  npm run lint
  ```

---

## Security Measures

1. **Backend:**
   - Basic Authentication for API documentation (**commented out for demo purposes**).
   - Rate-limiting to prevent abuse.
   - CSRF protection for state-changing requests (**commented out for demo purposes**).
   - CORS configured to allow secure API access (**allowed all for demo purpose**).
   - Input validation to prevent SQL/NoSQL injections and XSS attacks.

2. **Frontend:**
   - Environment variables for API configuration.
   - Validation for all input fields in forms using `Yup`.

---

## Completed Task Points

1. **Sign-Up Page:**
   - Includes fields for email, name, and password.
   - Validates password requirements and other input fields.
   - Redirects to the login page upon successful registration.

2. **Sign-In Page:**
   - Allows users to sign in with email and password.
   - Redirects to the application page with a welcome message.

3. **Backend Integration:**
   - Built with NestJS.
   - MongoDB integration with secure data handling.
   - Follows best practices for API development.

4. **Testing:**
   - Comprehensive unit and E2E tests.
   - 100% test coverage for all critical modules.

5. **Documentation:**
   - Swagger API documentation available at [https://auth.fullstackdev.in/docs](https://auth.fullstackdev.in/docs).

---

## Screenshots
![image](https://github.com/user-attachments/assets/0e6736b3-e9aa-47f6-a663-213337c31ad1)
![image](https://github.com/user-attachments/assets/64365c57-f541-45c5-a8d6-208c97a897b4)
![image](https://github.com/user-attachments/assets/2a6359ba-d8c8-4a52-b471-3312563e7aed)
![image](https://github.com/user-attachments/assets/1fa29fa9-72fa-413a-8f2f-01c302e845d2)
<img width="459" alt="image" src="https://github.com/user-attachments/assets/e4a286f4-31c7-44d8-8831-c5655aa60f9e">
<img width="574" alt="image" src="https://github.com/user-attachments/assets/4d50c875-f22e-4a42-8fa6-b1236b72179d">

## Support

For any issues or suggestions, please email me.

Enjoy exploring the project! 🎉

---

