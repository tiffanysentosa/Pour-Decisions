# Pour-Decisions 🍷👯‍♀️
**Pour Decisions** is an educational web application designed to help users learn about wine pairings through interactive features. It guides users on how to pair different wines with various dishes, enhancing their culinary experiences. The application includes detailed profiles of wines, a dynamic learning interface, and a quiz feature to test knowledge.

#### Features
- **Home Page**: Start your journey into wine pairing. Simple and inviting with a button to dive into the wine profiles.
- **Wine Profiles**: Learn about different wines, their characteristics, and what dishes they pair best with.
- **Interactive Quiz**: Test your knowledge by matching wines with the right dishes through a drag-and-drop quiz interface.
- **Progress Tracking**: Track which wines have been viewed and learned with visual feedback directly in the user interface.

#### Tech Stack
- **Frontend**: HTML, CSS, JavaScript (with jQuery and AJAX for asynchronous web calls)
- **Backend**: Flask (Python), handling routing, session management, and server-side logic
- **Database**: Uses server-side storage to track user progress and manage quiz data.
- **External Libraries**:
  - Bootstrap for responsive layout and modal dialogs.
  - jQuery UI for enhanced interactions like drag-and-drop.

#### JavaScript Functionality
- **modalManager.js**: Manages modal popups for wine details and controls the end-of-lesson triggers.
- **quiz.js**: Handles the quiz interactions, including drag-and-drop functionality and progression through quiz questions.
- **seenWineTracker.js**: Tracks which wines have been viewed to provide feedback and help users monitor their learning progress.
- **timeStamper.js**: Marks the start time when a user begins the learning session, useful for activity logging and user engagement metrics.

#### Setup and Installation
1. **Clone the repository**: Get the code from the GitHub repository.
2. **Environment setup**: Ensure Python and Flask are installed. Setup a virtual environment if needed.
3. **Dependency Installation**: Install necessary Python packages and other dependencies as listed in `requirements.txt`.
4. **Running the Application**:
   - Start the server by running the Flask application script.
   - Access the application through the local web browser at the specified port.

#### Usage
Navigate through the application using the navbar. Start learning by clicking on "wine profile" or test your knowledge directly by selecting "quiz". Use the interactive elements such as clicking on wine glasses to view detailed information and drag the appropriate wine to the dish in the quiz.

### Future Enhancements
- **User Accounts**: Implement user authentication to save individual progress and custom quizzes.
- **More Interactive Elements**: Include more detailed quizzes and interactive elements such as matching flavors and aromas.
- **Mobile Responsiveness**: Enhance the mobile user experience by improving touch interactions and mobile-specific layouts.

This README provides a comprehensive guide to using and understanding the "Pour Decisions" wine learning platform.
