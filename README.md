# Quill

**Quill** is a secure client-server chat web application that allows users to send quick doodles. The drawing functionality streams in real-time, enabling users to see each other's drawings as they are created.

---

## Features

- **Real-Time Chat**: Send and receive messages instantly.
- **Quick Doodles**: Draw and share doodles in real-time.
- **Secure Communication**: Ensures secure client-server interactions.
- **Responsive Design**: Works seamlessly across devices.

---

## Tech Stack

### Frontend
- **Framework**: Vue.js
- **Real-Time Drawing**: HTML5 Canvas with Fabric.js or Konva.js
- **UI/UX**: TailwindCSS + Vuetify

### Backend
- **Framework**: Django
- **Real-Time Communication**: Django Channels for WebSocket support
- **Authentication**: Google Sign-in

### Database
- **Primary Database**: PostgreSQL for structured data (e.g., user accounts, chat history)
- **Real-Time Data**: Redis for in-memory storage of active doodles and real-time messaging

---
