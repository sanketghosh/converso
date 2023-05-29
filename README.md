# Converso

Converso is a real-time chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to engage in instant messaging, create chat rooms, and communicate with other users in real-time.

<!-- ![Converso Demo](converso-demo.gif) Replace with a demo gif or screenshot -->

## Features

- User authentication and authorization
- Real-time messaging using WebSocket protocol
- Create and join chat rooms
- View online/offline status of users
- Intuitive user interface

## Technologies Used

- TailwindCSS: Styling for the user interface
- React.js: Frontend library for building user interfaces
- Express.js: Backend framework to handle API routes and WebSocket connections
- Socket.IO: Library for real-time bidirectional communication
- Node.js: Runtime environment for server-side JavaScript
- MongoDB: Database to store user details, chat rooms, and messages

## Installation

To run Converso locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/converso.git
```

2. Install the dependencies for the server and client:

```bash
cd converso
npm install
cd client
npm install
```

3. Create a `.env` file in the api directory and provide the necessary environment variables:

```bash
MONGO_URI=your_mongodb_connection_string
```

4. Start the development server:

```bash
npm run dev
```

5. Open your web browser and visit http://localhost:3000 to access Converso.

## Usage

- Create a new account or log in with your existing credentials.
- Join a chat room and start conversing with other users in real-time.
- Customize your user profile and avatar.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please create a new issue or submit a pull request.
