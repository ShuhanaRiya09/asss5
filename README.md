# Project Title: Quiz System

## Project Summary
This project is a simple Quiz System that allows an admin to add multiple-choice questions (MCQs) to a quiz bank and a student to take a quiz with random questions from the quiz bank. The system supports user authentication for both admin and student roles, enabling admins to manage the quiz content and students to participate in the quizzes.

## Prerequisites
- Java (Latest version)
- IDE of your choice (e.g., IntelliJ IDEA, Eclipse)

## How to Run
1. Clone the repository.
2. Open the project in your preferred IDE.
3. Run the `UserLogin` class.

## Project Structure
- `src/main/java`
  - `UserLogin` - Main class to run the application.
  - `QuizQuestionsEditor` - Class representing the functionality for adding multiple-choice questions and managing the quiz bank.
  - `StudentQuizPlay` - Class for quiz play as a student.
- `src/resources`
  - `users.json` - File containing user information.
  - `quiz.json` - File containing quiz questions.

## Usage
### For Admin User
1. Enter your username and password.
2. If authenticated as an admin, the system prompts you to add new questions to the quiz bank.
3. Continue adding questions until you press 'q' to quit.

### For Student User
1. Enter your username and password.
2. If authenticated as a student, the system prompts you to start the quiz.
3. Answer 10 random questions from the quiz bank.
4. Receive feedback based on your score.