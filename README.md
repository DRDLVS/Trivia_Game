# Quiz Game Project

This is a simple quiz game implemented in Python. The game uses Object-Oriented Programming (OOP) principles to manage the questions and user interactions. The project consists of four main components: data handling, main script, question modeling, and quiz logic.

## Project Structure

- **data.py**: Contains the list of questions in the form of a dictionary.
- **main.py**: The main script that initializes the quiz game and controls the game flow.
- **question_model.py**: Defines the `Question` class.
- **quiz_brain.py**: Defines the `QuizzBrain` class that manages the quiz logic.

## How It Works

### data.py

This file contains a list of dictionaries, each representing a question with its category, type, difficulty, question text, correct answer, and incorrect answers.

### main.py

This is the main script that runs the quiz game. It imports the required classes and data, creates question objects, and starts the quiz.

### question_model.py

This file defines the `Question` class, which models a quiz question with text and answer attributes.

### quiz_brain.py

This file defines the `QuizzBrain` class, which contains methods to manage the quiz logic, such as checking answers, keeping track of the score, and moving to the next question.


## Features

- **Object-Oriented Design**: The project is structured using classes to model questions and manage quiz logic.
- **Dynamic Question Handling**: The quiz can handle any number of questions defined in `data.py`.
- **Real-Time Feedback**: The user receives immediate feedback on their answers and can see their current score.

Enjoy the quiz game and feel free to extend it with more features and questions!
