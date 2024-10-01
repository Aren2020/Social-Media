# Authentication and Social Media System

## Features

1. **User Authentication**:
   - Registration
   - Login
   - Logout
   - Password editing
   - Password reset

2. **User Profiles**:
   - Custom user profile models
   - Authentication using email

3. **Social Authentication**:
   - Login with Facebook, Twitter, Google
   - Implemented using Python Social Auth and OAuth 2.0

4. **HTTPS Development Server**:
   - Served using Django Extensions

5. **Automatic Profile Creation**:
   - Profiles are automatically created for new users

6. **Many-to-Many Relationships**:
   - Custom form behavior for specific tasks

7. **JavaScript Bookmarklet**:
   - Share images from other websites

8. **Image Thumbnails**:
   - Created using the easy-thumbnails app

9. **AJAX-based Views**:
   - Implemented using JavaScript Fetch API
   - Infinite scrolling for image lists

10. **Subscription System**:
    - Many-to-many relationships with an intermediate model

11. **Activity Stream**:
    - Created using generic relations
    - Optimized query sets

12. **Django Signals**:
    - Signal receiver function for denormalizing related object counts
    - Application configuration classes for loading signal handlers

13. **Django Debug Toolbar**:
    - Added for debugging and performance tuning

14. **Redis Integration**:
    - Installed and configured Redis
    - Used for storing item views and creating image rankings

## Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/Aren2020/Social-Media.git
   cd Social-Media
   ```
2. **Create and activate a virtual environment:**
   ```sh
   python -m venv env
   source env/bin/activate
   ```
3. **Install the dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
4. **Apply migrations:**
   ```sh
   python manage.py makemigrations
   python manage.py migrate
   ```
5. **Run the development server:**
   ```sh
   python manage.py runserver
   python manage.py runsslserver (run the server using HTTPS necessary for social authentication to work)
   ```
