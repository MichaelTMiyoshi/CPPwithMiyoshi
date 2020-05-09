# Goal Sheet 07

**Problem GS07-01 (concession stand)**

Write a program that acts as the cash register of a concession stand (of a movie theater for example).  You need to have a minimum of popcorn, drinks that use an enum called sizes (like in the example code).  You also need to have at least two more items that the user can buy.  Decide the prices for things in such a way that the enumerated data is not the price.  Calculate the total and the tax.  The tax must be calculated in a separate function, where you return the tax only.  Output the price, tax, and total cost (price + tax) on separate labeled lines.  As an extension, you could make sure the user does not want more items or let the user choose how many items at what sizes.

**Problem GS07-02 (personal data)**

Write a program that gets personal data from the user.  The personal data will be held in a struct that has first name, middle name, last name (all three strings), age, and phone number (also a string).  You may add more data to your struct.  Get the data from the user, then output the data to the user who will make sure it is correct.  If not correct, the user should input the data again.  If the data is correct, you can tell the user the data will be handled with the utmost care.  As an extension, send the data in a struct from a function to the calling function (main()).

**Problem GS07-03 (playing cards) ([pair programming](https://github.com/MichaelTMiyoshi/CPPwithMiyoshi/blob/master/Problems/PairProgramming.md))**

Create a struct for a playing card.  The struct will have two enum data types.  One for the suits and one for the designation.  The struct will also have face values for each card from 1 to 13 and a unique number for its place in the deck (I suggest you used 0-51).  So your struct will have four things, suit, designation, face value and location.  You may also have a string for the name of the card, which will tell you its designation and suit (i.e. Jack of Diamonds).

Write a function that receives a random number (parameter) and returns a card from a 52-card deck.  Then, write a calling program that deals five random cards.  The random cards may have the same suits, designations, and values.  Display these five cards to the screen.  If you decide to have a string for the card, you may just display the string.  The string should tell you the designation and suit (i.e. Queen of Hearts).  [Note: There is a hierarchy of suits.  They are ranked from lowest to highest: clubs, diamonds, hearts, spades.]

If you would like to look ahead, you may use a vector to hold a deck of cards.  Otherwise, you can just have a large switch or if structure in your function that returns a card.  Either way, you may end up dealing more than one of the same card with your random numbers.  That is okay for now.

**Problem GS07-04 (distance between points)**

Write a program that calculates the distance between two points.  Make a struct for a 2D point which will have float values.  Declare two points from this one struct.  The user will input the values for the x- and y-values in the main() function of your program.  Then, you will send the two points to a function which calculates the distance between the points and returns the single value to the calling function to be displayed there.  Remember that the distance between two points whose coordinates are (x1, y1) and (x2, y2) is:
```
distance = sqrt( (y2 - y1)² + (x2 - x1)² )
where sqrt() is the square root of what is in parentheses.
```

**Problem GS07-05 (slope of a line)**

Write a program that calculates the slope of a line.  Make a struct for a 2D point with float values.  Make a struct for a line which has 2 points.  The user will input the data for two points.  Make sure that the line is really a line (not the same points) and that it is not vertical.  If the two points are equal, have the user input the points again (or at least the second one).  If the line is vertical, tell the user that the slope is infinite.  If the line is not vertical, send the line to a function that returns the slope.  Output the slope in the calling function.  Remember that the slope of a line with points P1(x1, y1) and P2(x2, y2) is calculated by the formula:
```
slope = (y2 - y1) / (x2 - x1)
```
As an extention, write the program so that it calculates both the distance between two points and the slope of the line (segment) between the two points.  Be careful to check the data.  If the user wants to input two points instead of a line, the points may be the same.  If they are the same, do not calculate the slope.  If the user wants to input a line, do not allow the points to be the same.  There are some tricky nuances to this program, make sure to test points and line segments.  You can make use of functions with different signatures as well as making functions from the last two programs.  One of the best ways to solve the problem is to make the slope function with two signatures, one that accepts two points, and one that accepts a line.


**Problem GS07-06 ([RPG](https://github.com/MichaelTMiyoshi/CPPwithMiyoshi/blob/master/Problems/RPG_Requirements.md) struct)**

Continue writing your RPG.  You must modify your user statistics to use a struct.  In other words, hold all your user data (name, health, hit points, and whatever other statistics you used) in one struct.  You may modify your RPG so that all your NPCs have the same characteristics (strength, speed, etc.) in a struct as well, but since you will be making them into objects later, you might want to hold off on that.  Especially, since you would need to modify your functions and other portions of your program to do so.
