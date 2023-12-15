
# Social Media Site using Django
### Overview
 This project is a social media platform developed using Django, featuring functionalities for multiple users, like and comment features, and specific login/register functionalities for regular users, alongside a special login for superusers.

### Functionality Highlights
- User Management: Supports multiple user accounts.
- Like and Comment: Users can like and comment on posts.
- User-Specific Login/Registration: Allows users to register and login with personalized accounts.
- Superuser Login: Special login access for superusers to manage administrative tasks.
### Technologies Used
- Django Framework: Utilized for structuring the application and handling backend operations.
- Django ORM: Manages the database schema and user-related data.
- HTML/CSS/JavaScript: Frontend design and interactivity.
- Database: Utilizes Django's default database or chosen database engine for data storage.
### Features
- User Management
  
  Registration: Users can register for an account with personalized details.
  
  Login: Registered users can log in using their credentials.
  
- Post Interactions
  
  Like: Users can like posts to express their interest or appreciation.
  
  Comment: Facility to add comments on posts.
  
- Administrative Features

  Superuser Access: A special login for administrative tasks:

  Access to user management functionalities.

  Ability to moderate posts and comments.

### Project Structure
- Models: Defines models for users, posts, likes, and comments.
- Views: Manages the backend logic for handling user requests and data processing.
- Templates: HTML templates for rendering frontend views.
- Static Files: CSS, JavaScript, and images for frontend styling and interactivity.
- Database Configuration: Configuration files related to database setup and management.
### Usage
#### Installation
  
1.Clone the repository.

2.Install necessary dependencies using pip install -r requirements.txt.

3.Configure the database settings in settings.py.

4.Run migrations using python manage.py migrate.

#### Running the Application
  
Launch the Django development server using python manage.py runserver.

Access the application via the provided URL.
