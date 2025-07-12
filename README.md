# CHAT-APPLICATION

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: Tushar Mishra

**INTERN ID**: CT06DF1763

**DOMAIN**: FULL STACK WEB DEVELOPMENT

**DURATION**: 6 WEEKS -- JUNE 5th,2025 to JULY 20th, 2025

**MENTOR NAME** : NEELA SANTHOSH KUMAR

# DESCRIPTION OF TASK PERFORMED :
During my internship at CODTECH, I developed a real-time chat application named RealChat. The primary objective of this project was to create a responsive, event-driven communication platform that enables multiple users to interact in real time through predefined chat rooms. The application was designed to ensure seamless message delivery, accurate user tracking, and a clean user interface optimized for performance.

The backend of RealChat was built using Node.js along with the Express.js framework to handle server-side routing, serve static assets, and manage real-time interactions. Real-time communication was achieved through Socket.IO, a JavaScript library that facilitates low-latency, bidirectional communication between clients and the server using WebSockets. This allowed for the instantaneous exchange of messages, join/leave notifications, and real-time updates within chat rooms.

The server maintains an in-memory data structure to map connected socket IDs to usernames and their respective rooms. This mechanism enables efficient tracking of user sessions, ensuring accurate room-level synchronization. Events such as user_joined, message_sent, and user_left are handled by Socket.IO’s event listeners on both the client and server sides. These events coordinate all client interfaces so that any updates in user activity or messages are instantly reflected across all connected users in a given room.

Upon launching the application, users land on a dashboard that requires them to input a unique username before proceeding. After successfully entering a name, users are presented with a list of predefined chat rooms and can select any room to join. Each room operates as an independent communication channel, allowing multiple participants to exchange messages simultaneously in a shared virtual space.

The frontend was developed using HTML, CSS, and vanilla JavaScript, ensuring responsiveness and clean usability across different screen sizes. The chat interface dynamically renders incoming messages and provides visual cues for user activity, such as join/leave alerts and message alignment to differentiate between users. A scrollable chat area allows users to navigate older messages, while message inputs are validated to prevent sending blank entries or entering a room without a valid username.

RealChat's user interface includes a basic navigation bar, room selection panel, and real-time status indicators. The layout is adaptive to various screen resolutions, offering a consistent experience on desktops and mobile devices. Frontend logic also handles socket event emissions, DOM manipulation for message display, and basic client-side validation.

Currently, RealChat operates using temporary in-memory storage without persistent databases. However, the application's architecture is modular and designed for scalability, making it suitable for future enhancements such as database integration, user authentication, chat history storage, and message encryption. The routing and event systems are separated to support extensibility and security improvements in future versions.

RealChat demonstrates a complete integration of frontend and backend components to deliver a functional, scalable, and real-time chat experience. It applies core full-stack web development techniques to support real-time interactions, maintain accurate session tracking, and provide a fluid user interface.

# OUTPUT OF THE TASK :
![Image](https://github.com/user-attachments/assets/cce16e0e-e2ae-4fc5-9576-b04e99dbc140)

![Image](https://github.com/user-attachments/assets/d5ae65f0-a888-4d24-8a3b-d5c3d4b8cf8f)
