# Full Stack Chatapp

## 📝 Introduction:

This project aims to provide a real-time chat experience that's both scalable and secure. With a focus on modern technologies, we're building an application that's easy to use and maintain.

## Detailed Workflow Description:

<div align="center">
  <img src="https://github.com/user-attachments/assets/f845a188-8e70-42f7-8577-30af38e83053" alt="workflow"/>
</div>

- **User Interaction:**
   - Users interact with the frontend application running in their browser. This includes actions like logging in, sending messages, and navigating through the chat interface. Frontend (React App): The frontend is responsible for rendering the user interface and handling user inputs. It communicates with the backend via HTTP requests (for RESTful APIs) and WebSocket connections (for real-time interactions).

- **Backend (Node.js/Express + Socket.io):**
   - The backend handles all the server-side logic. It processes API requests from the frontend to perform actions such as user authentication, message retrieval, and message storage. Socket.io is used to manage real-time bi-directional communication between the frontend and the backend. This allows for instant messaging features, such as showing when users are typing or when new messages are sent.

- **MongoDB (Database):**
   - MongoDB stores all persistent data for the application, including user profiles, chat messages, and any other relevant data. The backend interacts with MongoDB to retrieve, add, update, or delete data based on the requests it receives from the frontend.

## ✨ Features:

* **Real-time Messaging**: Send and receive messages instantly using Socket.io 
* **User Authentication & Authorization**: Securely manage user access with JWT 
* **Scalable & Secure Architecture**: Built to handle large volumes of traffic and data 
* **Modern UI Design**: A user-friendly interface crafted with React and TailwindCSS 
* **Profile Management**: Users can upload and update their profile pictures 
* **Online Status**: View real-time online/offline status of users 

## 🛠️ Tech Stack:

* **Backend:** Node.js, Express, MongoDB, Socket.io
* **Frontend:** React, TailwindCSS
* **Containerization:** Docker
* **Orchestration:** Kubernetes
* **Web Server:** Nginx
* **State Management:** Zustand
* **Authentication:** JWT
* **Styling Components:** DaisyUI

## 🔧 Prerequisites:

* **[Node.js](https://nodejs.org/)** (v14 or higher)
* **[Docker](https://www.docker.com/get-started)** (for containerizing the app)
* **[Git](https://git-scm.com/downloads)** (to clone the repository)

## 🚀 Running the Application with Docker Compose

To run the application using Docker Compose, follow these steps:

1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Ensure Docker and Docker Compose are installed:**
   ```sh
   docker --version
   docker-compose --version
   ```

3. **Run the application using Docker Compose:**
   ```sh
   docker-compose up --build
   ```

   This command builds and starts the required services (frontend, backend, and MongoDB).

4. **Access the application:**
   - **Frontend:** Open [http://localhost](http://localhost) in a browser.
   - **Backend API:** Accessible at [http://localhost:5001](http://localhost:5001).
   - **MongoDB:** Running internally on port `27017`.

5. **To stop the services:**
   ```sh
   docker-compose down
   ```

## 🔩 Step by Step Process:

* **[Click Here](https://harsh-thakkar.notion.site/kubernetes-minikube-chat-app-1c756dc9a68580f5b52ae9a0de4a67dc)** (Notion Page with complete code and flow screenshots)

## 📚 Project Snapshot:

<div align="center">
  <img src="https://raw.githubusercontent.com/Harsh971/FullStack-Chat-App---Minikube/refs/heads/main/img1.png" alt="first_page"/>
</div>


