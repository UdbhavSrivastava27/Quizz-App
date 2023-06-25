#Quiz App

The Quiz App is a web application that allows users to participate in a quiz by answering multiple-choice questions. The application is built using HTML, CSS, and JavaScript, and it incorporates various features such as fetching questions from a JSON file, tracking the user's progress through a progress bar, and storing high scores in local storage.


#Demo:
https://udbhavsrivastava27.github.io/Quizz-App/

#Features
Fetching Questions:

The application fetches questions from a JSON file, which can be easily modified to add or remove questions. The JSON file contains an array of question objects, each consisting of the question itself, multiple options, and the correct answer.

Multiple-Choice Format:

Each question is presented in a multiple-choice format, where the user can select one option as their answer. The user can only proceed to the next question after selecting an option.

Progress Tracking: 

The application includes a progress bar that visually indicates the user's progress through the quiz. As the user answers each question, the progress bar updates accordingly, providing a visual representation of how far the user has progressed.

High Score Storage: 

The application utilizes the browser's local storage to store and display the high scores achieved by users. When a user completes the quiz, their score is compared to the existing high scores, and if it is higher, it is stored in local storage. The high scores are then displayed on a separate page for users to see.

#Technologies Used

HTML5
CSS3
JavaScript
JSON

#Usage

To use the Quiz App, follow these steps:

Clone the repository or download the source code.

Open the index.html file in a web browser.

The quiz will start automatically, presenting the user with the first question and a list of options.

Select one option by clicking on it.

Proceed to the next question by clicking the "Next" button.

Repeat steps 4 and 5 until all questions have been answered.

After answering the last question, the application will display the user's score and indicate whether it is a high score or not.

Click the "View High Scores" button to see the high scores achieved by users.

On the high scores page, the user can choose to play again by clicking the "Play Again" button.

#Customization
The Quiz App can be customized according to your requirements. Here are some possible customizations:

Modifying Questions:

Open the questions.json file and add or remove question objects as needed. Each question object should contain the following properties: question (the question text), options (an array of options), and answer (the index of the correct option).

Styling:

The appearance of the application can be customized by modifying the CSS code in the styles.css file. You can change colors, fonts, layout, and other visual aspects to match your desired design.

Adding Features: 

You can extend the application by adding new features such as a timer, hints, or a leaderboard. JavaScript can be modified in the script.js file to implement additional functionality.

Compatibility
The Quiz App is compatible with modern web browsers, including Chrome, Firefox, Safari, and Edge. It does not require any external libraries or dependencies.
