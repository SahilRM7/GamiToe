# 🎮 Real-Time TIC TAC TOE Game using Django & WebSockets

A multiplayer Tic Tac Toe game built using Django and Django-Channels that enables two players to compete in real-time using WebSocket communication.

---

## 📄 About the Project

This web-based game allows two players to compete against each other without any need for login or signup. Players simply enter their name, generate a game code, and share it with a friend to start playing instantly.

---

## ⚙️ Key Features

- 🚫 No login/signup required  
- 🙋‍♂️ Enter your name and generate a unique game code  
- 🔗 Share the code with a friend to start a match  
- ⚡ Real-time multiplayer experience using WebSockets

---

## 🛠 Technologies Used

- **Django** – Backend development
- **Django Channels** – WebSocket support for real-time features
- **Redis / Memurai** – Channel layer backend for Django Channels
- **SQLite** – Default local database
- **DTL (Django Template Language)** – Template rendering engine
- **JavaScript** – WebSocket client-side logic
- **Bootstrap 5** – Responsive UI design
- **FontAwesome** – Icon library
- **HTML/CSS** – Frontend structure and styling

---

## 🖥 User Interface

The application features an intuitive interface:

1. Enter your name to begin a game.
2. Share the auto-generated game code with a friend.
3. The friend uses the code to join the game.
4. Play Tic Tac Toe in real-time, powered by WebSockets.

---

## 🚀 Installation Guide

To run this project locally, follow these steps:

### 1. Clone the Repository
    git clone https://github.com/SahilRM7/GamiToe.git
### 2. Navigate to the project directory: cd GamiToe
### 3. (Optional) Create and activate a virtual environment: python3 -m venv venv and source venv/bin/activate
### 4. Install the required dependencies: pip install -r requirements.txt
### 5. Set up the database by running migrations: python manage.py migrate
### 6. Create a superuser for accessing the admin panel: python manage.py createsuperuser
### 7. Start the development server: python manage.py runserver
### 8. Open a web browser and access the application at http://localhost:8000
