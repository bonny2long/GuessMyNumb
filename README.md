# Guess My Number
A simple number-guessing game showcasing core JavaScript skills like DOM manipulation and event handling.


Guess My Number! 🎉
This project is a simple number-guessing game developed as part of Jonas Schmedtmann's course. The game helps players guess a random number between 1 and 20, providing feedback on their guesses and tracking their score. Along the way, I learned key concepts in JavaScript and web development, as detailed below.


Overview
In "Guess My Number!", players enter guesses in an input field, and the game provides feedback: whether the guess is too high, too low, or correct. The player's score decreases with every wrong guess, and the high score is updated if the player wins. A reset button allows the player to restart the game with fresh settings.

How It Works
Number Generation:

A random secret number between 1 and 20 is generated at the start of the game.

User Interaction:

Players input their guesses using a text field.

Feedback is provided on whether the guess is correct or not.

Score Tracking:

The score decreases with each wrong guess.

A high score is saved if the player wins with a higher score than previously recorded.

Reset Functionality:

A reset button allows players to restart the game with original settings, including a new secret number.

What I Learned
This project provided valuable insights into core JavaScript and web development concepts, including:

1. DOM Manipulation
Selecting and modifying elements dynamically using document.querySelector.

Updating text, styles, and input fields based on user actions.

2. Event Listeners
Adding click event listeners for interactive buttons.

Reacting to user input and triggering game logic dynamically.

3. Functions and Reusability
Writing reusable functions like displayMessage to streamline code and avoid redundancy.

4. Control Flow
Implementing conditional logic using if, else if, and else to handle different game scenarios.

5. Variables and Game State
Managing state variables such as score, secretNumber, and highscore to keep track of gameplay.

6. Random Number Generation
Using Math.random and Math.trunc to create random numbers in a defined range.

7. Dynamic Styling
Changing the appearance of elements (e.g., background color and width) dynamically to enhance user experience.

8. Debugging Skills
Using console.log to debug and understand program behavior during development.

Technologies Used
HTML: For structuring the webpage.

CSS: For styling the webpage.

JavaScript: For game functionality and interactivity.

How to Run
Clone the repository to your local machine.

bash
git clone <repository-url>
Open the index.html file in your browser.

Start playing the game!

Acknowledgments
This project is part of Jonas Schmedtmann's course, which offers practical and engaging ways to learn JavaScript and web development. The course made it easy to grasp complex concepts and apply them effectively in real-world scenarios.
