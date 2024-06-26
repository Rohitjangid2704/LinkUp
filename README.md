```markdown
# Chat Application

This is a real-time chat application built with the MERN stack, Socket.io for real-time messaging, and JWT authentication for secure user access.

## Features

- **Real-time Messaging:** Utilizes Socket.io for instant messaging between users.
- **Authentication & Authorization:** JWT-based authentication system ensures secure access to chat features.
- **Online User Status:** Tracks and displays online status of users in real-time.
- **Global State Management:** Zustand used for managing global application state.
- **Error Handling:** Comprehensive error handling implemented both on the server and client sides.

## Screenshots

![Screenshot 1](screenshots/screenshot1.png)
![Screenshot 2](screenshots/screenshot2.png)

## Tech Stack

- **Frontend:** React, TailwindCSS, Daisy UI
- **Backend:** Node.js, Express.js, MongoDB
- **Real-time Communication:** Socket.io
- **State Management:** Zustand
- **Authentication:** JWT

## Getting Started

To get a local copy up and running, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/chat-app.git
   ```
   
2. **Install dependencies:**
   ```bash
   cd chat-app
   npm install
   ```

3. **Set up environment variables:**
   - Create a `.env` file in the root directory.
   - Define environment variables like `MONGODB_URI`, `JWT_SECRET`, etc.

4. **Start the development server:**
   ```bash
   npm run dev
   ```

5. **Open your browser:**
   - Visit `http://localhost:3000` to see the application running.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
```

