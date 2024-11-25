

# Full-Stack Authentication Demo

Welcome to the Full-Stack Authentication Demo. This project demonstrates a complete user authentication system built using modern technologies.

### Live Demo

- **Frontend Demo**: [https://auth.fullstackdev.in/](https://auth.fullstackdev.in/)
- **API Documentation**: [https://auth-api.fullstackdev.in/docs](https://auth-api.fullstackdev.in/)
- **API Base URL**: [https://auth-api.fullstackdev.in/](https://auth-api.fullstackdev.in/)

![image](https://github.com/user-attachments/assets/0e6736b3-e9aa-47f6-a663-213337c31ad1)
![image](https://github.com/user-attachments/assets/64365c57-f541-45c5-a8d6-208c97a897b4)
![image](https://github.com/user-attachments/assets/2a6359ba-d8c8-4a52-b471-3312563e7aed)
![image](https://github.com/user-attachments/assets/1fa29fa9-72fa-413a-8f2f-01c302e845d2)








---

## Repositories

- **API Repository**: [https://github.com/devshridhar/api](https://github.com/devshridhar/api)
- **Frontend Repository**: [https://github.com/devshridhar/frontend](https://github.com/devshridhar/frontend)

---

## Features

### Backend Features

1. **User Authentication**:
    - API endpoints for user signup and signin.
    - Validation for password strength (minimum 8 characters, at least one letter, number, and special character).
    - Secure JWT-based token generation.

2. **API Documentation**:
    - Fully documented API using Swagger.
    - Swagger UI hosted for easy testing and understanding of endpoints.

3. **Security Measures**:
    - Basic Authentication for Swagger documentation.
    - CORS policies to restrict cross-origin access.
    - CSRF protection.
    - Helmet for securing HTTP headers.
    - Rate-limiting to prevent abuse.
    - Sanitized user inputs to mitigate SQL/NoSQL injection and XSS attacks.

### Frontend Features

1. **Authentication Pages**:
    - Sign-up and sign-in forms with client-side validation.
    - Redirect to a welcome page upon successful authentication.

2. **Integration with Backend**:
    - Configurable API base URL through environment variables.
    - Handles authentication errors and displays appropriate messages.

3. **UI Design**:
    - Designed using Material-UI (MUI) for a clean and professional look.

4. **Security Measures**:
    - All user inputs are validated on both client and server sides.
    - Strict handling of error messages to prevent information leaks.

---

## Installation and Setup

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or later)
- [MongoDB](https://www.mongodb.com/) (local or cloud-based)
- [npm](https://www.npmjs.com/)

### Backend Setup

1. Clone the API repository:
   ```bash
   git clone https://github.com/devshridhar/api.git
   cd api
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:
   Create a `.env` file and provide the necessary environment variables:
   ```env
   PORT=3000
   MONGO_URI=mongodb://localhost:27017/auth-api
   JWT_SECRET=your_secret_key
   ```

4. Start the backend server:
   ```bash
   npm run start:dev
   ```

5. API will be accessible at:
   ```
   http://localhost:3000/
   ```

### Frontend Setup

1. Clone the frontend repository:
   ```bash
   git clone https://github.com/devshridhar/frontend.git
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:
   Create a `.env` file and specify the backend API URL:
   ```env
   REACT_APP_API_URL=http://localhost:3000
   REACT_APP_PORT=3001
   ```

4. Start the frontend:
   ```bash
   npm run start
   ```

5. The frontend will be accessible at:
   ```
   http://localhost:3001/
   ```

---

## Testing

### Backend Testing

1. Run unit tests:
   ```bash
   npm run test
   ```

2. Run end-to-end tests:
   ```bash
   npm run test:e2e
   ```

3. Generate a test coverage report:
   ```bash
   npm run test:cov
   ```
<img width="459" alt="image" src="https://github.com/user-attachments/assets/e4a286f4-31c7-44d8-8831-c5655aa60f9e">
<img width="574" alt="image" src="https://github.com/user-attachments/assets/4d50c875-f22e-4a42-8fa6-b1236b72179d">


   

### Frontend Testing

1. Run tests:
   ```bash
   npm run test
   ```

2. Run linter for code quality:
   ```bash
   npm run lint
   ```

---

## Security Measures Summary

### Backend

- Rate-limiting: Limits the number of requests per user to prevent abuse.
- CSRF protection: Mitigates cross-site request forgery attacks.
- Input validation: Sanitizes inputs to prevent SQL/NoSQL injection and XSS.
- Helmet: Secures HTTP headers.

### Frontend

- Client-side validation for all forms.
- Error handling to avoid exposing sensitive information.
- Secure integration with the backend API using environment variables.

---

## License

This project is licensed under the MIT License.

---

## Support

For any issues or suggestions, please raise an issue in the respective repositories.

Enjoy exploring the project! 🎉

---
