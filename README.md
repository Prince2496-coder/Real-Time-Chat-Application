# Real-Time Chat Application

A full-stack real-time chat application built using Spring Boot, React, MongoDB, WebSocket, Docker, and Docker Compose.

## Features

* Create chat rooms
* Join existing chat rooms
* Real-time messaging using WebSockets
* Persistent message storage with MongoDB
* Dockerized frontend and backend
* Docker Compose orchestration
* Responsive user interface

## Tech Stack

### Backend

* Java 21
* Spring Boot
* Spring Data MongoDB
* Spring WebSocket
* Maven

### Frontend

* React
* Vite
* Axios
* SockJS
* STOMP.js

### Database

* MongoDB

### DevOps

* Docker
* Docker Compose
* Docker Hub

## Project Structure

```text
CHAT_X
│
├── back-end
│   ├── src
│   ├── Dockerfile
│   └── pom.xml
│
├── front-chat
│   ├── src
│   ├── Dockerfile
│   └── package.json
│
└── docker-compose.yml
```

## Run Locally

### Clone Repository

```bash
git clone <repository-url>
cd CHAT_X
```

### Start Application

```bash
docker compose up -d
```

### Access Application

Frontend:
http://localhost:5173

Backend:
http://localhost:8080

MongoDB:
localhost:27018

## Docker Images

Backend:

* princeohlyan09/chat_back

Frontend:

* princeohlyan09/chatfront

## Future Enhancements

* JWT Authentication
* Private Messaging
* User Profiles
* Online/Offline Status
* Read Receipts
* Message Reactions
* File Sharing

## Author

Prince

GitHub:
https://github.com/Prince2496-coder
