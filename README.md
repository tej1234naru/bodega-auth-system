Bodega Auth System

Overview  
The Bodega Auth System is a Node.js-based authentication solution designed during an internship at the startup Bodega. Its primary function is to provide secure user login and registration, leveraging JWT tokens for session management. Only authenticated users can access protected areas, thereby enhancing both data security and the overall integrity of the service.

Key Features

- API endpoints for user registration and login.
- JWT-based token authentication for secure session handling.
- Password hashing utilizing recognized cryptographic standards.
- Rigorous form validation to prevent invalid or insecure submissions.

Technical Stack

- Node.js
- Express.js
- MongoDB
- Git & GitHub

File Structure

- /controllers: Contains business logic and handler functions.
- /models: Defines MongoDB data schemas and models.
- /routes: Express route definitions for APIs.
- package.json: Lists project metadata and dependencies.
- README.md: Project documentation.

Setup Instructions

1. Clone the repository from GitHub.
2. Execute npm install to install dependencies.
3. Start the server with npm start.
4. Use Postman or curl to interact with the API endpoints.

Example Usage

- POST /api/login
- POST /api/register

Each endpoint returns a JSON response containing a JWT token and user data.

Author  
Tejaswini Naru  
GitHub: https://github.com/tej1234naru
