# My Rock Paper and Scissor Game Project using JavaScript
Introduction : 

Rock, paper, and scissors game is a simple fun game in which both the players have to make a rock, paper, or scissors. It has only two possible outcomes a draw, or a win for one player and a loss for the other player. We will be designing the game using JavaScript where a player will be playing against the computer. In total there will be 10 moves. The player has to choose one option among the rock, paper, and scissors. A random option will be generated from the computer’s side and the one who wins will get one point every time. After 10 moves are over the final result will be displayed on the screen with a button to restart the game. The game will be completely responsive so that it can be played on every device.

**Link to project:** https://savicode-rockpaperscissors.netlify.app/

![alt tag](https://tinypic.host/images/2022/06/05/Screenshot-60.png)

## How It's Made:
The HTML Layout:

HTML gives the basic structure of the game. styles.css file is linked in the head tag which will be used for styling the HTML.

Description of elements use in code is below:

A div with the class title is used to display the title on the screen.
A div with a class score contains two more div which will display the score of the player and computer.
Div with the class move just displays a text and div with class movesleft will show the number of moves left before the game ends.
A div with a class option contains three button rock, paper, and scissors which the user can use to give the input.
A div with the class result will display the result of every move and the final result after 10 moves and the button with class reload will allow reloading the game.

The CSS Styling:

This styling is used for the game. You can change the styles as per your needs.

The logic using JavaScript:

The main logic of the game is created by using JavaScript. We will be performing DOM manipulation so basic knowledge of JavaScript is enough to build the game.

Follow steps 

Create a function game() that will contain all the logic of the game.
Inside the function declare three variables playerScore, computerScore, moves which will keep the record of the player’s score, computer’s score, and moves completed respectively.
Create a function playGame() and inside the function use DOM manipulation to get hold of all the three buttons we created in HTML for player input. Create an array playerOptions which will contain all three buttons as its elements. Similarly, create an array for computer options.
Use forEach() loop on playerOptions so that we can add an event listener on all buttons with a single piece of code. Inside the loop increment moves counter by 1 display moves left on the screen by subtracting moves from 10. Generate a random value for the computer option and compare it with the player’s input.
Create a function winner() which will receive two arguments one the player’s input and the other the computer’s option  The function will decide who wins the point among the player and computer.
Create a function gameOver() which will display the final result with reload button. The function will be called when moves will become equals to 10.
Call the playGame() function inside the game() function.
Now call the game() function at the end of the file.

**Tech used:** HTML, CSS, JavaScript

Here's where you can go to town on how you actually built this thing. Write as much as you can here, it's totally fine if it's not too much just make sure you write *something*. If you don't have too much experience on your resume working on the front end that's totally fine. This is where you can really show off your passion and make up for that ten fold.








