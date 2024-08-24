# Real-time-chat-application-project-using-Python-and-Django
Real-time Chat application
# Real-Time Chat System with Django

Welcome to the Real-Time Chat System project! This project demonstrates how to build a real-time chat application using Django and Django Channels.

## Features

- **Real-Time Messaging**: Send and receive messages instantly using WebSockets.
- **User Authentication**: Secure login and logout functionality.
- **Responsive Design**: User-friendly interface for chat and authentication.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python
- Django
- Django Channels
- Daphne

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/ChakraborttySouvik/real-time-chat-application-project-using-Python-and-Django
   cd your-repo-name
2. **Install Dependencies**

Create a virtual environment and install the required packages.
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
pip install -r requirements.txt


3.**Set Up the Database**

Run the migrations to set up your database.
python manage.py migrate

4.**Run the Development Server**

Start the Django development server.
python manage.py runserver

python manage.py runserver
Open Your Browser


Navigate to http://localhost:8000 to see the application in action.
**Project Structure**
DjangoChat/
│
├── ChitChat/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── consumers.py
│   ├── models.py
│   ├── routing.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   └── templates/
│       └── chat/
│           ├── chatPage.html
│           └── loginPage.html
│
├── DjangoChat/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── manage.py
└── requirements.txt

**Screenshots**



How It Works
WebSocket Connection: The chat application uses WebSockets for real-time communication.
Routing: Messages are routed through Django Channels.
Templates: HTML templates are used for user interfaces, including login and chat pages.
Contributing
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

**Contact**
For any questions or feedback, you can reach out to Souvik.Chakrabortty123@gmail.com
