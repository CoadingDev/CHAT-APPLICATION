# CHAT-APPLICATION

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: Tushar Mishra

**INTERN ID**: CT06DF1763

**DOMAIN**: FULL STACK WEB DEVELOPMENT

**DURATION**: 6 WEEKS -- JUNE 5th,2025 to JULY 20th, 2025

**MENTOR NAME** : NEELA SANTHOSH KUMAR

# DESCRIPTION OF TASK PERFORMED :

During my internship at CODTECH, I developed a real-time chat application called RealChat. RealChat targets offering smooth real-time communication between users using pre-defined chat rooms by integrating robust backend technologies and a responsive, user-friendly interface.
RealChat is implemented with Socket.IO, a JavaScript library for event-driven real-time communication between server and clients via WebSockets. In the backend, I employed Node.js with Express.js for routing and static file serving. This deployment provides a light and scalable environment well suited for real-time applications.

The app begins with a dashboard that requires users to register a unique name before they can move forward. Upon entering a valid name, users are presented with a list of pre-defined chat rooms and can select one to join. Each room is a specialized conversation space where several users are able to interact at once.

Once within a room, users may exchange messages in real-time. Active users and their room memberships are tracked by the server through an in-memory data structure mapping the socket ID to a username and a room. The user_joined, message_sent, and user_left events are processed via Socket.IO's event handling system, synchronizing all the clients and keeping the chat interface quick.

The frontend is constructed from HTML, CSS, and JavaScript with clean design and usability in mind. Each message that is sent is dynamically rendered within the chat window with update-in-real-time functionality and visual differentiation between various users. The chat area is scrollable for checking past messages, and the interface contains useful cues such as join/leave notifications.

In order to improve usability, RealChat implements error handling for cases like sending an empty message or trying to join a room without a username. The UI also features a basic navigation bar, a room selector panel, and adaptive layout for varying screen sizes.

Despite the fact that the application itself now operates with temporary in-memory data (no database), its architecture accommodates future growth, such as user authentication, persistent chat history, and encrypted messaging.

Overall, RealChat demonstrates how real-time applications can be efficiently built using a focused tech stack. This project allowed me to apply practical full-stack development skills and better understand the principles of live communication systems, user session management, and responsive interface design.

# OUTPUT OF THE TASK :

