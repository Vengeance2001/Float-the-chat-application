# Float-the-chat-application


This is a full-stack chat application built using the MERN stack, consisting of MongoDB, Express.js, React.js, and Node.js. The application allows users to create accounts, log in securely, and engage in real-time chat with other users.

## Features

- **User Authentication:** Secure user authentication system using JWT (JSON Web Tokens) for token-based authentication.
- **Real-Time Messaging:** Real-time messaging functionality using WebSockets for instant communication between users.
- **User Profiles:** Users can create profiles, update their information, and upload profile pictures.
- **Message History:** Chat history is stored in MongoDB to ensure that users can view previous messages upon logging in.
- **Responsive Design:** Responsive and mobile-friendly design using React.js for seamless user experience across devices.

## Technologies Used

- **Frontend:** React.js, React Router, Redux for state management, Socket.IO for real-time messaging.
- **Backend:** Node.js, Express.js, MongoDB (Mongoose) for database management, JWT for authentication.
- **Styling:** CSS3, Bootstrap or Material-UI for styling components.
- **Deployment:** The application can be deployed on platforms like Heroku, AWS, or DigitalOcean.

## Getting Started

1. Clone the repository: `git clone https://github.com/your-username/mern-chat-app.git`
2. Navigate to the project directory: `cd mern-chat-app`
3. Install dependencies for both the client and server: `npm install`
4. Create a `.env` file in the server directory and add environment variables (e.g., MongoDB connection string, JWT secret).
5. Start the backend server: `npm start` in the server directory.
6. Start the frontend development server: `npm start` in the client directory.
7. Open your browser and navigate to `http://localhost:3000` to view the application.

## Contributing

Contributions are welcome! Feel free to open issues for bug fixes, feature requests, or any improvements you'd like to see. Pull requests are also appreciated.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
