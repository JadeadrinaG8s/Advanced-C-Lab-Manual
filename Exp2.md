EXP NO:2 C PROGRAM FOR PASSING STRUCTURES AS FUNCTION ARGUMENTS AND RETURNING A STRUCTURE FROM A FUNCTION
Aim:
To write a C program for passing structure as function and returning a structure from a function

Algorithm:
1.	Define structure numbers with members a and b.
2.	Declare variable n of type numbers.
3.	Prompt the user to enter values for a and b.
4.	Input values for a and b into n using scanf.
5.	Call the add function with n as an argument.
6.	Print the result returned by the add function.
7.	Return 0
 
Program:

//type your code here
```
#include <stdio.h>

struct numbers
{
    int a;
    int b;
};

struct numbers add(struct numbers n)
{
    n.a = n.a + n.b;
    return n;
}

int main()
{
    struct numbers n, result;

    printf("Enter values of a and b: ");
    scanf("%d %d", &n.a, &n.b);

    result = add(n);

    printf("Result = %d", result.a);

    return 0;
}
```



Output:

//paste your output screenshots here
```
Enter values of a and b: 10 20
Result = 30
```




Result:
Thus, the program is verified successfully
