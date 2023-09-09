# Simon-Game (Overview)
- This is a Simon Game in which there are 4 coloured tiles are given in which the pattern are to be choosen by the user as the increase of levels the pattern length increase and the wrong input will end the game.

## [Table Of Content]
- [Simon Game(Overview)](#Siomon-Game)
- [Live Link](#Live-Link)
- [My Approach](#My-Approach)
- [Tools Used](#Tools-Used)
- [What I learned through this project](#What-I-Learned-through-this-project)
- [Acknowledgments](#Acknowledgments)
## Live-Link

## My-Approach
- First I made the basic structure using HTML in index.html file.
- Then I designed the page with CSS in style.css file.
- After that I made the rest functionalities of the game using Javascript in simon.js file. This Process involved below steps(steps are also marked in simon.js file):
- Step1: Made a function named nextSequence() which generated random color and performed the given set of instruction on being for each level.
- Step2: Then I added animation and sound to be played on the tile which is randomly choosen within the nextsequence function.
- Step3: This is the second most tricky part. It involved adding eventlistener which gives the information about the input of user.
- Step4: It involved adding a start() function which sets all the values and conditions and starts the level1 of the game.
- Step5: This is the most tricky part.It involved storing input of user and comparing it with pattern generated by newSequence function and proceeding the game as per rules of the game.
- Also made various functions for different tasks like playSound(), gameLost(), start(),etc.
- Game Project got completed.

## Tools Used:
- HTML5
- CSS
- Javascript
- CSS Grid

## What I learned through this project
- With this project, I got a deeper understanding of many concepts of javascript.
- Using jquery to animate-- code:$("."+randomChosenColor).fadeOut(100).fadeIn(100).fadeOut(100).fadeIn(100);
- Understood the working of eventListerners and their callback functions
- used JSON.stringify(userInput)===JSON.stringify(gamepattern) to compare arrays in javascript. This method converts arrays into JSON string and then compares them.
- Learned the usage of setTimeout function and its callback. **code:**setTimeout(nextSequence(),2000);
- More practice on DOM manipulation.
- Build the major logic of game on my own which boosted my understanding of javascript code: *//getting user input color in userinput array userInput.push(userChosenColor); i++;

## Acknowledgments
- Web Developement Bootcamp by Angela Yu

