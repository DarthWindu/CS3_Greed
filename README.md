# CS3_Greed
Greed Project for CS3

Bebo H., Pujit M., Brian T., Arnav S.

Assignment: 
For this assignment, you will create a computer controlled greed strategy. You will extend the GreedStrategy class with a class that plays greed. You will need to create the choose method, programming it so that it makes the choice in response to the number of dice, available options, and bank, that results in the highest average points per turn.

You can use the strategy evaluator provided to test your strategy over a large number of turns. When you make a change you can decide if it is an improvement or a decrease. This lets you try various ideas. You can also use the practiceGreed method to try out ideas before you program them.

There is a sample strategy included in the Greed-Code folder called RandomStrategy that chooses at random among the options.

Give your class a name which is your last name followed by your first name, followed by GreedStrategy. If you are partnered with someone, include both your last names instead.

-----------------------
RULES
On your turn:

Start with 6 dice.
1.	Throw your dice. 
2.	Set aside one or more groups of dice that have value (see below). 
  o	Add the points from those groups to your bank. 
  o	If you cannot set aside any dice, you lose ALL the points in your bank and your turn is over.
  o	If you set your sixth die aside, you get all six dice back and may continue rolling.
3.	Decide whether you want to throw again.
  o	If so, go to step 1 and throw remaining dice.
  o	If not, add your bank to your total points and your turn is over

Point values of groups:

Six of a kind	5000
123456		1000
1111			1000
666			600
555			500
444			400
333			300
222			200
One 1		100
One 5		50
====================================================================================
