College mini Project 
# Social Book - Django Social Media Application

## Project Overview

**Social Book** is a Django-based social media application developed as a mini-project for the Master in Computer Application (MCA) degree. The platform is designed to provide core social networking functionalities while prioritizing data privacy, security, and user control.

---

## 🛠 Features

* 
**User Authentication**: Secure registration with email verification, login/logout, and password reset.


* 
**Profile Management**: Customizable user profiles including bios, avatars, and cover photos.


* 
**Content Creation**: Create, edit, and delete posts containing both text and images.


* 
**Social Interactions**: Real-time "Like" system and commenting capabilities on posts.


* 
**Social Connections**: Follow and unfollow system to build a personalized network.


* 
**Discovery**: Search functionality to find users by username and explore trending content.



---

## 💻 Tech Stack

* 
**Backend**: Python 3.x and Django 4.x.


* 
**API**: Django REST Framework.


* 
**Frontend**: HTML5, CSS3, JavaScript , and Tailwind CSS/Bootstrap.


* 
**Database**: PostgreSQL or SQLite.


* 
**Deployment**: Gunicorn, Nginx, and AWS/DigitalOcean.



---

## 🏗 System Architecture

The application utilizes the **Model-View-Template (MVT)** architectural pattern:

* 
**Model**: Defines the data structure and database schema (User, Post, Comment, Like).


* 
**View**: Contains business logic and handles user requests.


* 
**Template**: Manages the presentation layer using HTML for the user interface.



---

## 🔒 Security

The project implements several security best practices to protect user data:

* 
**CSRF Protection**: Enabled by default to prevent cross-site request forgery.


* 
**XSS Prevention**: Utilizes Django's template auto-escaping.


* 
**SQL Injection Prevention**: Secured via the Django Object-Relational Mapping (ORM).


* 
**Password Hashing**: Uses PBKDF2 for secure credential storage.



---

## 🚀 Installation and Setup

### Prerequisites

* Python 3.8+ 


* pip 


* virtualenv 



### Setup Steps

1. **Clone the Repository**:
```bash
git clone https://github.com/username/django-social-media.git
cd django-social-media



2. **Create Virtual Environment**:
```bash
python -m venv venv
source venv/bin/activate # On Windows: venv\Scripts\activate


3. **Install Dependencies**:
```bash
pip install -r requirements.txt


4. **Database Configuration**:
```bash
python manage.py makemigrations
python manage.py migrate


5. **Create Admin Account**:
```bash
python manage.py createsuperuser


6. **Run Development Server**:
```bash
python manage.py runserver




