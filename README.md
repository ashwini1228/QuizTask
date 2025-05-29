# QuizTask

*COMPANY*: CODTECH IT SOLUTIONS 
*NAME*: ASHWINI GAWALI 
*INTERN ID*: CT4MPFZ 
*DORAIN*: FRONT END DEVELOPMENT 
*DURATION*: 4 MONTHS 
*MENTOR*: NEELA SANTOSH 

This project is a simple, interactive quiz application built using HTML, CSS, and JavaScript. It allows users to test their general knowledge through a series of multiple-choice questions. Designed to be lightweight and user-friendly, the app presents one question at a time and provides immediate feedback based on the user's answer selection. It is responsive and functional across modern web browsers and devices.

The main structure of the app is defined in the index.html file. It includes a container with a heading for the quiz, a section where the question and answer buttons are dynamically rendered, and a navigation button that advances the user to the next question. The HTML is clean and semantic, making it easy to read and modify.

The visual design and layout are handled through the style.css file. The quiz app features a centered layout with rounded containers, custom fonts, and clearly styled buttons. Color feedback is provided to indicate correct and incorrect answers. Green is used for correct selections and red for incorrect ones. The "Next" button is hidden until the user selects an answer, at which point it becomes visible, allowing progression to the next question.

Functionality is managed entirely with JavaScript in the script.js file. The app initializes by displaying the first question from a predefined set. Each question object contains the question text and four answer options, with one marked as correct. When an answer is selected, the script highlights the correct and incorrect choices and disables further interaction with the buttons. The user can then proceed by clicking the "Next" button. At the end of the quiz, the total score is displayed with an option to restart the quiz.

The quiz logic includes dynamic DOM manipulation, event handling, and basic conditional logic. Questions are stored as objects in an array, and the app iterates through them using an index. Functions such as startQuiz(), showQuestion(), selectAnswer(), and showScore() handle the quiz lifecycle, from loading the first question to displaying the final score. The code is written with simplicity and clarity, making it ideal for beginners learning how to work with JavaScript-driven web interfaces.

Although the app is currently static, it serves as a solid foundation for future enhancements. Potential improvements include adding a backend to store user scores, loading questions from a remote database or API, supporting different categories or difficulty levels, implementing a timer, and tracking progress across sessions.

In summary, this project demonstrates how a basic quiz game can be implemented using only frontend technologies. It’s a great educational tool for those new to JavaScript and web development. The app's modular structure and straightforward logic make it easy to customize and expand into a more comprehensive quiz or educational testing system.

![Image](https://github.com/user-attachments/assets/d2f55766-9059-4707-a2ff-ed06b4cba04a)
![Image](https://github.com/user-attachments/assets/ee87f369-f7da-49b0-bb09-2d1eebcef86a)
