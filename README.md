# PingMe chat application
A Real-Time Chat Application built with Django and WebSockets
PingMe is a real-time chat application that allows users to send instant messages, engage in private conversations, and stay connected seamlessly. Built with Django, Django Channels, and WebSockets, it provides a smooth and responsive chatting experience.

# Features
###  ✅ User Authentication – Secure login, registration, and logout.
### ✅ Real-Time Messaging – Powered by WebSockets for instant communication.
### ✅ Private Chats – One-on-one messaging between users.
### ✅ Online Status – See who's active in real-time.
### ✅ Responsive UI – Works on desktop and mobile.

# Technologies Used
Backend: Django, Django Channels

Frontend: HTML, CSS, JavaScript, WebSockets

Database: SQLite (can be configured for PostgreSQL)

Authentication: Django’s built-in auth system

# Installation
Prerequisites
Python (3.8+)

Django (4.0+)

Redis (for production WebSocket support)

# Setup
Clone the repository:

git clone https://github.com/smithmoh/PingMe.git
cd PingMe
Create and activate a virtual environment:

python -m venv venv
venv\Scripts\activate     # Windows
Install dependencies:

pip install -r requirements.txt
Run migrations:

python manage.py migrate
Start the development server:

python manage.py runserver
Access the app at:
http://127.0.0.1:8000/

Running with WebSockets (ASGI)
For real-time functionality, use:

daphne PingMe.asgi:application
(Ensure Redis is running if in production.)
# Other
Screenshots


Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.
