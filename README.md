<img width="1080" height="349" alt="image" src="https://github.com/user-attachments/assets/622897d3-dc45-4ff0-8846-8fb1753540bb" />
<img width="2880" height="1628" alt="image" src="https://github.com/user-attachments/assets/ca001857-dd65-4fd1-afff-f9f824fc542a" />


SkyLearn – Feature-Rich Learning Management System

SkyLearn is a modern, lightweight, and open-source Learning Management System (LMS) built with the Django web framework. It is designed for schools, colleges, and educational institutions, offering robust features for managing courses, students, lecturers, and assessments in a streamlined way.
This project is ideal for developers looking to learn Django, build portfolio projects, or contribute to an educational tool that simplifies learning management.


Key Features

Admin Dashboard

View school demographics, analytics, and statistics

Manage students (Add, Update, Delete)

Manage lecturers (Add, Update, Delete)

Manage academic sessions, semesters, and courses

Student Features

Enroll in or drop courses

View assessments and grades by semester

Automatically calculated total scores, averages, points, and grades

View personalized grade comments (Pass, Fail, or Pass with Warning)

Access registration slips and grade results in PDF format

Lecturer Features

Submit student scores for attendance, exams, assignments

Upload course videos and documentation

Quiz & Assessment Features

Store and track quiz results for each user

Randomized question order for quizzes

Resume incomplete quizzes for logged-in users

Limit quizzes to one attempt per user

Multiple question types: Multiple Choice, True/False, and soon Essay

Custom messages for passing or failing a quiz

Monitor success rates by category

Mark essay questions efficiently

Other Features

Page access restrictions based on user roles

User-friendly interface for all roles

Secure session management and permissions


Requirements

Python 3.8+

Django framework and dependencies listed in requirements.txt

Installation Steps

Clone the repository:

git clone https://github.com/SkyCascade/SkyLearn.git


Navigate to the project folder and create a virtual environment:

cd SkyLearn
python -m venv venv
venv\Scripts\activate      # Windows
source venv/bin/activate   # Linux/Mac


Install dependencies:

pip install -r requirements.txt


Set up environment variables:

Copy .env.example to .env

Customize variables as needed

Run database migrations:

python manage.py migrate


Create a superuser for admin access:

python manage.py createsuperuser


Start the development server:

python manage.py runserver


Access the application:

Open your browser at http://127.0.0.1:8000

Contributing

We welcome contributions! You can start by picking tasks from the TODO.md file. Whether it’s improving features, fixing bugs, or adding new functionality, your help is appreciated.

References

Quiz system inspired by: Django Quiz

Support

If you find this project useful, consider giving it a ⭐️ on GitHub!
