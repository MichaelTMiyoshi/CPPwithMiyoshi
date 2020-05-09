# Goal Sheet 06

**Problem GS06-01 (fraction reducer)**

Write a program that reduces fractions using a function.  The function will return an int and have two int arguments.  The returned int will be the greatest common factor (GCF).  The function prototype and the GCF function from the example in the chapter may be used as a starting point.

**Problem GS06-02 (square root reducer) ([pair programming](https://github.com/MichaelTMiyoshi/CPPwithMiyoshi/blob/master/Problems/PairProgramming.md))**

Write a program that simplifies integer square roots.  (You probably never thought you would need to do that again after you finished the math class where you did it.)  You do this by determining if the user’s input number has any square factors.  You then return the factor (not squared) from your function.  For instance, if you pass the number 72 to your reducer, it has the square factor 36.  Your function would return the factor 6 (6 * 6 = 36).  In your calling function (presumably main), you would output that the reduced number is 6√2.  You do not need to use the square root symbol.  You can instead say the reduced number is 6 times the square root of 2.  Or something to that effect.  If you would like to use the square root symbol (√), its ASCII value is 251 (decimal).  Your function prototype should look like the following:
```
int RootReducer(int number);
```

**Problem GS06-03 (fortune cookie)**

Write a program that is passed a number and a string (or just a number) and gives the user a fortune.  You will decide which fortune (of ten possible) based on the number that is passed to the function.  Then, the function will pass the fortune back to the calling function.  Output the fortune in the calling function.  You must loop the program (in main()) so that the user can keep getting fortunes until opting to quit.  (As an extension, use a random number to determine the number you pass to the function instead of getting the number from the user.)  Your function prototype may look like one of the following:
```
void FortuneCookie(int num, string & fortune);
string FortuneCookie(int num);
```

**Problem GS06-04 (function maze)**

Write a program that uses functions for the rooms (minimum of 12) of a maze.  The maze should have beginning and ending points.  Between are rooms that can be traversed via your own system.  The best way to do the maze is not to call rooms from other rooms but to have a loop in the main() function and call the rooms based on a room variable (like the example with three rooms).  Your maze must have a minimum of 12 rooms and the user may travel to each one.  You may have one path or multiple paths that get you to the exit.  You might even put a story to it, although that is really part of the major program.

**Problem GS06-05 (word reverser)**

Write a program that reverses the characters in a string.  While there is a function that does this, using it does not count as writing a function.  Your function should pass one or two strings to it.  (See prototypes below.)  The first function has two arguments, the first argument is where the reversed string ends up and the second is where the original is passed.  The second function gets passed the original string and returns the reversed string.  Make sure to keep the original string unchanged in the calling function (presumably main()).  Output the original and reversed strings in the calling function.  Your function prototype might look like one of the following prototypes:
```
void Reverser(string & reversed, string original);
string Reverser(string original);
```

**Problem GS06-06 ([RPG](https://github.com/MichaelTMiyoshi/CPPwithMiyoshi/blob/master/Problems/RPG_Requirements.md) functions)**

Create functions for movement, rooms, fighting and such.  [_**Note** to my students: You will be concluding your major project in the first part of the second semester._]
