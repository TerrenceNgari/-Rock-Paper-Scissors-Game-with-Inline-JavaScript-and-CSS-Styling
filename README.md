Seminar Session 8
Assignment: Build a Rock, Paper, Scissors Game with Inline JavaScript and CSS Styling
Objective:
Create an interactive Rock, Paper, Scissors game using HTML, inline JavaScript, and CSS. This
assignment will reinforce JavaScript logic, conditional statements, and user interaction with
onclick events, while also focusing on styling the page with images and colors.
Instructions
1. Game Setup:
o Create a webpage with the title “Rock Paper Scissors” and a main heading that
displays "Rock Paper Scissors".
o Add a short paragraph with instructions for the game, such as “Choose Rock,
Paper, or Scissors to play against the computer.”
2. Button Design with CSS:
o Create three buttons labeled "Rock," "Paper," and "Scissors" that represent the
player’s choices in the game.
o Style the Buttons with Images:
 Use CSS to add an image (Rock, Paper, or Scissors) to each button
background. You can use background-image in CSS to set the image for
each button.
 Adjust the button size, padding, and font color to make the images clear
and visually appealing.
o Page Styling:
 Set a background color for the page to make it visually engaging.
 Center-align the content, and add some padding or margin to space out
the elements on the page.
3. JavaScript Logic:
o For each button, add an onclick attribute that triggers JavaScript code when the
button is clicked.
o Your code should:
 Generate a random move for the computer using Math.random() to
select between Rock, Paper, and Scissors.
 Using Math.random for Random Selection: Since
Math.random() generates a number between 0 and 1, divide this
range into three equal parts for Rock, Paper, and Scissors:
 Rock: If the random number is between 0 and <1/3
 Paper: If the random number is between 1/3 and <2/3
 Scissors: If the random number is between 2/3 and <1
 This way, each choice has an equal probability (approximately
33%) of being selected.
 Compare the player’s move (based on the button clicked) with the
computer’s randomly generated move.
 Use if-else statements to determine the game’s result (win, lose, or tie)
based on traditional Rock, Paper, Scissors rules:
 Rock beats Scissors
 Scissors beat Paper
 Paper beats Rock
4. Display the Result:
o Display the result in a message that shows the player’s choice, the computer’s
choice, and the game outcome.
o Use alert to display the result in a popup, or for an additional challenge, use
document.write or add a <p> element to show the result directly on the page.
5. Requirements:
o Random Computer Move: Generate a computer move each time a button is
clicked.
o Result Calculation: Use conditional logic to determine and display the
outcome (win, lose, or tie).
o Styling and Instructions: Ensure the page has clear instructions, a visually
appealing color scheme, and buttons with appropriate images.
6. Bonus Challenge:
o After building the game, try displaying the results directly on the page instead of
using alert.
o Add a “Reset” button to clear the results or reset the game.
Deliverables:
• Submit your code with output in a .pdf file
