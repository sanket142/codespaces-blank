College mini Project 
# Social Book - Django Social Media Application

This project is a high-level Python web application built using the **Django framework**. It implements a secure, user-centric social networking platform that addresses common challenges like data privacy and security vulnerabilities.

## 🚀 Key Features

* 
**User Authentication**: Robust registration with email verification, secure login/logout, and password reset mechanisms.


* 
**Profile Management**: Users can customize their profiles, upload avatars and cover photos, and view followers/following lists.


* 
**Post Management**: Full CRUD operations for posts including text and image uploads, with a dynamic news feed.


* 
**Social Interactions**: Real-time likes, comments, and the ability to follow or unfollow other users.


* 
**Content Discovery**: Functionality to search for users by username and explore trending content.



## 🛠️ Technology Stack

* 
**Backend**: Python 3.x, Django 4.x, Django REST Framework.


* 
**Frontend**: HTML5, CSS3, JavaScript, jQuery, and Tailwind CSS/Bootstrap.


* 
**Database**: PostgreSQL or SQLite.


* 
**Development Tools**: Git, VS Code/PyCharm, Postman, and Django Debug Toolbar.



## 🏗️ System Architecture

The application follows the **Model-View-Template (MVT)** pattern:

* 
**Model**: Defines the data structure (Users, Posts, Comments, Likes).


* 
**View**: Handles business logic and processes user requests.


* 
**Template**: Manages the user interface and presentation layer.



## 🔒 Security Measures

The platform prioritizes security by implementing:

* 
**Built-in Protection**: Default defense against CSRF, XSS, and SQL injection.


* 
**Secure Authentication**: Password hashing using PBKDF2 and permission-based access controls.


* 
**Data Security**: Environment variables for sensitive data and HTTPS enforcement for production.



## 📈 Performance Highlights

* 
**Average Page Load Time**: 1.2 seconds.


* 
**API Response Time**: 10 milliseconds.


* 
**Concurrent Users**: Efficiently handles up to 100 simultaneous users.



## 📝 Setup and Installation

(Based on Annexure J)

1. **Prerequisites**: Ensure Python 3.8+ and `pip` are installed.
2. **Clone the Repository**: `git clone https://...`
3. **Virtual Environment**: Create and activate a `virtualenv`.
4. **Dependencies**: Install required packages using `pip install -r requirements.txt`.
5. **Database**: Run migrations using `python manage.py migrate`.
6. **Run Server**: Start the development server with `python manage.py runserver`.
