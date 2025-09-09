

MERN Chat App — Real-time Chat with Socket.io

A real-time chat application built with the MERN stack (MongoDB, Express, React, Node) and Socket.io for real-time messaging. This repo contains both the backend (API + Socket server) and the frontend (React client).

Live demo link: https://chat-app-omega-bice.vercel.app/

Features:-
1)Real-time messaging with Socket.io (one-to-one and rooms)

2)User authentication (JWT)

3)Persisted chat messages in MongoDB

4)Online user presence

5)Responsive React UI

Tech Stack:-
1)Frontend: React (Vite or Create React App), React Router

2)Backend: Node.js, Express

3)Database: MongoDB (Atlas or local)

4)Real-time: Socket.io

5)Auth: JWT (JSON Web Tokens)

6)Context API for state management

Prerequisites:-
1)Node.js (v16+ recommended)

2)npm or yarn

3)MongoDB (Atlas or local instance)

Run Locally (development):-
Start backend (development)
# from /backend
npm run dev
# or
nodemon server.js

This should start Express on http://localhost:5000 (or your configured PORT) and host the Socket.io server.

Start frontend (development)
# from /frontend
npm run dev       # if using Vite
# or
npm start         # if using CRA

#Screenshots
<img width="1826" height="975" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/ff4c2f1c-7521-4c30-a741-2810f4ffff9a" />



