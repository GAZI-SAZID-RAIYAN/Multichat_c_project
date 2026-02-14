# Multichat_c_project
A real-time socket programming project in C for handling multiple client-server communications.

## 📂 Project Structure
* `server.c`: The core server logic for handling multiple connections.
* `client_gui.c`: The client-side interface for sending and receiving messages.
* `.vscode`: Configuration files for the development environment.

## 🚀 Getting Started
1. **Compile the Server:**
   `gcc server.c -o server -lws2_32`
2. **Compile the Client:**
   `gcc client_gui.c -o client -lws2_32`
3. **Run:** Start `server.exe` first, then launch multiple `client.exe` instances to chat.

## 🛠️ Requirements
* GCC Compiler (MinGW for Windows)
* WinSock2 Library
