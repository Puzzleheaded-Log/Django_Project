Learning Log - Django Web Application
This project is a web application built with Django as part of my learning journey while studying the book Python Crash Course by Eric Matthes.

The application allows users to track learning topics and related entries in a structured way.

🛠️ Technologies Used
Python 3
Django Framework
HTML / CSS
Bootstrap
SQLite (default Django database)
🚀 Features
The application provides the following features:

User registration (sign up)
User authentication (login / logout)
Create new topics
Edit existing topics
Delete topics
Add entries under each topic
Edit entries
Delete entries
Clean and responsive UI using Bootstrap
📦 Project Structure
The project is organized into multiple Django apps:

accounts – handles user authentication
learning_logs – manages topics and entries
templates – contains HTML templates for the application
💻 How to Run the Project Locally
Follow these steps to run the project on your local machine:

1. Clone the repository
git clone cd

2. Create a virtual environment
python -m venv venv

3. Activate the virtual environment
Windows:

venv\Scripts\activate

Mac/Linux:

source venv/bin/activate

4. Install dependencies
pip install -r requirements.txt

5. Apply database migrations
python manage.py migrate

6. Run the development server
python manage.py runserver

7. Open in browser
http://127.0.0.1:8000/

📚 Learning Source
This project was developed while studying:

Python Crash Course by Eric Matthes
It helped me understand:

Django fundamentals
Authentication system
CRUD operations
Web application structure
📌 Future Improvements
Add user profile pages
Improve UI/UX design
Add search functionality for topics
Deploy project online (Heroku / Render / Railway)
👨‍💻 Author
Developed as part of my Python & Django learning journey.
