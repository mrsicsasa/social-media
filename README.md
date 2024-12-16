# Social Media Application

This project is a social media application built using Django. The application provides core functionalities typical of a social platform, such as user authentication, post creation, interaction, and user management.

## Features

### User Authentication
- **Signup**: Users can create a new account with their email and password.
- **Signin and Logout**: Existing users can log in and log out securely.

### Account Management
- **Account Settings**: Users can update their account information, including profile details.

### Post Management
- **Uploading Posts**: Users can create and upload posts with images and captions.
- **Post Feed**: A dynamically updated feed displays posts from users.
- **Like Posts**: Users can like or unlike posts.

### User Interaction
- **Profile Page**: View and edit user profiles.
- **Follow/Unfollow**: Users can follow or unfollow other users.

### Search and Recommendations
- **Search User**: Search functionality to find other users.
- **User Suggestions**: Personalized suggestions for users to follow.

### Additional Features
- **Download Images**: Users can download images from posts.
- **Post Feed Updates**: The feed updates dynamically with new posts and interactions.

## Technologies Used

- **Django**: Backend framework for building the application.
- **SQLite**: Default database for development purposes.
- **HTML/CSS**: For designing user interfaces.
- **JavaScript**: For interactive and dynamic front-end elements.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/social-media-django.git
   ```

2. Navigate to the project directory:
   ```bash
   cd social-media-django
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:
   ```bash
   python manage.py migrate
   ```

5. Run the development server:
   ```bash
   python manage.py runserver
   ```

6. Access the application in your browser at [http://127.0.0.1:8000](http://127.0.0.1:8000).

## Future Enhancements

- Implementing real-time notifications.
- Adding support for private messaging between users.
- Enhancing the post feed with infinite scrolling.
- Integrating advanced analytics for user engagement.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Feel free to contribute to this project by submitting pull requests or reporting issues!

