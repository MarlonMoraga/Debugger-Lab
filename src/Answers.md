# CSCI 121: Debugger Lab Answers

#### Name: Marlon Moraga
##### Date: 1/29/15








## Question 1:

The reason why the cutoff is not a parameter to the method of playturn in the PigGame class because cutoff is a contructor.It's receiving information to create the die or the game.


## Question 2:

The following code thats going to print is 0

## Question 3:

In the the pigGame class, I would move numBusts in Playturn under the while loop and in the if statement because the score will be always be 0 and numBusts will add +1 which wont affect the code at all. 

## Question 4: 

Based on my understanding, the problem would be located in the die.java class because I notice that the math in one of the code inside this class is causing an ifinite loop.

## Question 5: 
The problem with the program was that the casting method was only only casting math.random which causes an infinite loop of 1. For example, the code ((int)Math.Random()*6)+1 was giving major problems. In addition, the int which is a casting method was only casting Math.Random giving the results of always being 1. I changed this by adding another parathese to the whole code. For example, (int)((Math.random() *6)+1).

## Question 6:
For the number 10: 100, 14,~7.1425.
For the number 15: 104, 15, ~6.93334. For the number 20: 103, 12, ~8.58334. For the number 25: 101 ,9, ~11.22221  