<h1>Hog</h1>

<h2>Description</h2>
Project consisted of the implementation of code to create a working version of The Game of Hog: a two player dice game.  The rules are as follows:

- Two players alternate turns trying to be the first to end a turn with at least GOAL points
- On each turn, the current player chooses some number of dice to roll, up to 10. That player's score for the turn is the sum of the dice outcomes. However, if any of the dice result in a 1, that player receieves a score of 1 for that turn.
- In a normal game of Hog, those are all the rules.  A couple other rules have been implemented to spice up the gameplay:

<b>Boar Brawl: </b> A player who rolls zero dice scores three times the absolute difference between the tens digit of the opponent’s score and the ones digit of the current player’s score, or 1, whichever is higher. The ones digit refers to the rightmost digit and the tens digit refers to the second-rightmost digit. If a player's score is a single digit (less than 10), the tens digit of that player's score is 0.

<b>Sus Fuss: </b> We call a number sus if it has exactly 3 or 4 factors, including 1 and the number itself. If, after rolling, the current player's score is a sus number, they gain enough points such that their score instantly increases to the next prime number.

Much of the code in the files other than hog.py and dice.py was provided by cs61a, an entry level computer science course offered by The University of California Berkeley.  Further resources and projects offered by the course can be found here: https://cs61a.org/



<h2>Languages Used</h2>

- Python

<h2>Program walk-through:</h2>

<br />
Download files and launch the GUI <br/>

<img src="https://i.imgur.com/q59Vlqv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enjoy a game of Hog!  <br/>

<img src="https://i.imgur.com/VyBqe2F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

