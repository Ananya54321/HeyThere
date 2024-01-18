---

# HeyThere Chat Application 🚀

HeyThere is a delightful chat application developed in Java Swing for the graphical user interface (GUI) and socket programming for communication. This application allows users to exchange messages in a chat-like interface.

---

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Contributing](#contributing)
- [License](#license)

## Features 🌟

- **Swing GUI**: Utilizes Java Swing for creating a user-friendly graphical interface.
- **Socket Programming**: Implements socket communication for real-time message exchange between clients and the server.
- **Message Formatting**: Dynamically formats messages to fit within a specified maximum width.
- **Time Stamps**: Displays time stamps for each message.

## Getting Started 🚀

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Java Development Kit (JDK) installed.
- Java Integrated Development Environment (IDE) for development (e.g., IntelliJ, Eclipse).

### Installation 🛠️

1. Clone the HeyThere repository:

    ```bash
    git clone https://github.com/your-username/HeyThere.git
    ```

2. Open the project in your preferred Java IDE.

3. Compile and run the `Client` class for the client-side application.

4. Compile and run the `Server` class for the server-side application.

## Usage 🚀

1. **Client Application:**
   - Launch the HeyThere client application.
   - Enter your message in the text field at the bottom.
   - Click the "Send" button to send the message.

2. **Server Application:**
   - Start the HeyThere server application.
   - The server listens for incoming messages from clients and displays them.

## Code Structure 🏗️

### Client Class

- The `Client` class manages the client-side GUI and handles user input.
- Messages entered by the user are sent to the server, and incoming messages are displayed in the GUI.

### Server Class

- The `Server` class handles socket connections from clients.
- Incoming messages are received, and the server broadcasts them to all connected clients.
