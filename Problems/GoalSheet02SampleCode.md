# Sample code for Goal Sheet 02

**For problem GS02-02**

```
/*	Name:  (Put your name here)
	Problem:  (Put the whole problem statement here, or use your own words.)
	Pseudocode:  (State your algorithm in English here.)
		Output message to the screen
		Declare and initialize variables
		Do some math and output results to screen
		Show modulus and output to screen
	Notes:  (Put any notes about your thoughts here)
	Maintenance log:
		Date:		Done:
		(Date here)	(What you did here)
*/
	// some comment
#include <conio.h>
#include <stdio.h>

int main()
{
	printf(“Division problems.\n\n”);	// output message to the screen
	int a = 3;
	int b = 4;
	int c = 7;
	float x = 3;
	float y = 4;
	float z = 7;

	c = a / b;
	printf(“a / b = %d\n”, c);	// int division
	z = x / y;
	printf(“x / y = %f\n”, z);	// float division
	c = x / y;
	printf(“x / y = %d\n”, c);	// float division into int variable
	z = a / b;
	printf(“a / b = %f\n”, z);	// int division into float variable
	c = a / y;
	printf(“a / y = %d\n”, c);	// mixed division into int variable
	z = x / b;
	printf(“x / b = %f\n”, z);	// mixed division into float variable
	c = a / (int) y;
	printf(“a / y = %d\n”, c);	// int division into int variable
	z = x / (float) b;
	printf(“x / b = %f\n”, z);	// float division into float variable

	c = a / b;
	printf(“a / b = %d\n”, c);	// int division
	int d = a % b;
	printf(“a %% b = %d\n”, d);	// modulus (remainder)

	printf(“Press the any key to continue.\n”);
	//_getch();	// Uncomment this line if your code runs but does not stay on the screen when finished.
	return 0;
}
```
