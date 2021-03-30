# Goal Sheet 12

**Problem GS12-01 (ellipse class)**

Write a class called ellipse and a program that tests the class.  The class must have the required element (instance variables) of an ellipse (r1, r2).  The class must also have a default constructor, methods to set the radii, methods to get each radius, a circumference method, and an area method.  The circumference and area methods must return the ellipse’s circumference and area.  Use the compiler’s built-in definition of PI in your code (remember the includes shown below, then you can use `M_PI` for Pi).  Notes: The area of an ellipse is `Pi * r1 * r2`.  The circumference of an ellipse is approximately `2 * Pi * sqrt (r1 * r2)` according to Johannes Kepler.
```
#define _USE_MATH_DEFINES	// get access to constants like M_PI
#include <math.h>
```

**Problem GS12-02 (rectangle class)**

Write a class called rectangle and a program that tests the class.  The class must have the required elements (instance variables) of a rectangle (length and width).  The class must also have a default constructor, a method(s) to set the instance variables, a method(s) to get the instance variables, a perimeter method, and an area method.  The perimeter and area methods must return the rectangle’s perimeter and area.

**Problem GS12-03 (right triangle class)**

Write a class called triangle and a program that tests the class.  The class must have the required elements (instance variables) of a right triangle (base and height).  The class must also have a default constructor, a method(s) to set the instance variables, a method(s) to get the instance variables, a perimeter method, and an area method.  The perimeter and area methods must return the rectangle’s perimeter and area.

**Problem GS12-04 (animal class)**

Write an animal class.  This class must contain the animal’s name and two character traits (one character/string data and one numerical).  Make methods to change and get data.  Then create a program that uses the class.  As an extension, use a text file to store the data.

**Problem GS12-05 (person class)**

Write a person class.  This class must contain a person’s first, middle, and last names as well as the person’s age and phone number.  Make methods to change and get data.  Then create a program that uses the class.  As an extension, use a text file to store the data.  Make sure that you can retrieve and modify the data from the file.

**Problem GS12-06 ([RPG](https://github.com/MichaelTMiyoshi/CPPwithMiyoshi/blob/master/Problems/RPG_Requirements.md) classes and finish)**

Write a Non-Player Character (NPC) class.  This class must contain the NPC’s data you already had (name, health, hit points) plus some other things.  You need to have a race (enumerated using enum that you create – orc, elf, dwarf, human, or whatever you choose – and they do not need to be those Tolkein created).  (You may have more, but not less data.)  Make methods to change and get data.  You must have at least two constructors, a default and one that takes all the data as arguments in the method call.  The default constructor must assign the elements randomly, while the constructor that has arguments, assigns the data appropriately.  Then complete the RPG.  Your NPC objects should be gathered together in a vector.  Look at the RPG requirements again (copied again in the next chapter) before turning it in.
