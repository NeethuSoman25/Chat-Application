#Chat Application
A simple and elegant chat application built using Django for the backend, along with HTML, CSS, and Bootstrap for the frontend interface. The application allows one-to-one communication between users with a structured and minimalistic design.

Features
User Authentication: Secure login functionality for users to access the chat platform.
User-Based Chatrooms:
The superuser (user1) can chat with any other user.
Regular users can only chat with the superuser.
Message Management: Real-time display of chat history for every user pair.
Responsive Design: Built with Bootstrap for a mobile-friendly and modern interface.
Technology Stack
Backend
Django Framework:
Handles user authentication, session management, and database interactions.
Provides structured views for managing chatrooms and messages.
Frontend
HTML and CSS: For building the structure and layout of the application.
Bootstrap: To ensure a responsive, visually appealing design.
Database
SQLite (default for Django): Stores user, chatroom, and message data.
Database Models
Users: Represents the application users.
Fields: id, username, password.

ChatRoom: Represents chatrooms between two users.
Fields: id, user1, user2.

Messages: Stores messages exchanged in a chatroom.
Fields: id, content, sender, chat_room, timestamp.

Setup Instructions
Prerequisites
Python (3.6 or above)
Django (latest version)
Bootstrap (linked via CDN in templates)
