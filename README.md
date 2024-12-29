# Quiz-System-Project
The Quiz System is a robust application designed to facilitate quiz creation, management, and participation. It offers functionalities for both users and administrators, ensuring a seamless experience from registration to result display. The system is ideal for educational institutions, training centers, or any environment requiring automated quiz management.

### Features
- User Features
    - User Login:
        Existing users can securely log in to access their quizzes.
  - New User Registration:
    Allows new users to create accounts by providing their details.
  - Password Reset:
    Enables users to reset their passwords if forgotten, maintaining security.
  - Take Quiz:
    Users can participate in quizzes based on the questions set by the admin.
  - View Results:
    Displays the quiz results immediately after submission, showing scores and performance.
- Admin Features
  - Admin Login:
    Secure access for administrators to manage the quiz system.
  - Add Questions:
    Admins can add new questions manually to the quiz database.
  - Update Questions:
    Allows modification of existing questions to keep the quiz content up-to-date.
  - View Questions:
    Provides a list of all questions in the system for review or editing.
  - Set Questions from File:
    Admins can upload a file containing multiple questions, simplifying quiz setup.
  - Delete Users:
    Remove users who are no longer part of the system or for any administrative reason.
  - View Users:
    Displays a list of all registered users for monitoring and management.
  - Show Results:
    Admins can view users' quiz performance, analyze results, and provide feedback.

### Tools, Platforms, and Languages
Front-End
  - Python tkinter is used to create a graphical user interface (GUI) that is intuitive, user-friendly, and responsive.
    
Back-End
  - Business Logic: Python is employed to handle all functional operations, such as user authentication, quiz management, and result calculation.
  - Database: SQLite is used to store and manage user accounts, quiz questions, and result data efficiently and reliably.
    
Key System Capabilities
1. Secure Authentication:
    - Separate login mechanisms for users and administrators ensure secure access and data segregation.
2. Dynamic Question Management:
    - Admins can effortlessly add, update, or delete questions, and even upload question files for faster quiz setup.
3. Result Tracking:
    - Results are displayed to users post-quiz, with admin access for detailed performance reviews.
4. Scalability:
    - The system is designed to handle a growing number of users and questions without performance degradation.
5. Reliability:
    - SQLite provides a robust database backend that ensures data integrity and quick retrieval.

### Workflow
1. User Registration:
    - New users register and gain access to the system.
2. Admin Question Management:
    - Admins set up questions via manual input or bulk upload.
3. Quiz Participation:
    - Users log in and take quizzes based on the set questions.
4. Result Display:
    - Results are immediately calculated and shown to users and available for admin review.
