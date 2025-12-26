# WebRTC Video Communication App

This project is a real-time communication application built using **ReactJS** for the frontend and **WebRTC with WebSocket** for the backend.  
WebSocket is used as a signaling server, while WebRTC handles peer-to-peer audio/video communication.

---
🔄 How It Works

1. Client connects to the WebSocket server
2. WebSocket server exchanges signaling data (offer, answer, ICE candidates)
3. WebRTC establishes a direct peer-to-peer connection
4. Audio/Video streams are shared between peers

## 📁 Project Structure

webrtc-project/
├── frontend/ # ReactJS frontend
│ ├── src/
│ ├── public/
│ └── package.json
│
├── backend/ # WebRTC + WebSocket backend
│ ├── server.js
│ └── package.json
│
└── README.md
