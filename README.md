#Float the MERN STACK chat application
This is a full-stack chat application built using the MERN stack, consisting of MongoDB, Express.js, React.js, and Node.js. The application allows users to create accounts, log in securely, and engage in real-time chat with other users.

![Screenshot 2024-04-06 163001](https://github.com/Vengeance2001/Float-the-chat-application/assets/120655373/f9fd29bd-90e6-4fb7-b976-75e6788cdd92)
![Screenshot 2024-04-06 162920](https://github.com/Vengeance2001/Float-the-chat-application/assets/120655373/2dd4e5cf-013d-4b20-8dbb-05d9cc16be9c)
![Screenshot 2024-04-06 162909](https://github.com/Vengeance2001/Float-the-chat-application/assets/120655373/b7d1576f-1d55-4349-bbee-195d54d7cbfc)





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
