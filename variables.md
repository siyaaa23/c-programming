A variable is a named memory location used to store data in a C program.
The value stored in a variable can be changed during program execution.

Example:
int age = 20;

Here:
int → data type
age → variable name
20 → value stored in the variable

2. Syntax
data_type variable_name;
Example:
int age;
float marks;
char grade;
We can also initialize while declaring:
int age = 20;
float marks = 85.5;
char grade = 'A';


4. Declaration vs Initialization
Declaration:
int age;
Only the variable is created; no value is assigned explicitly.

Initialization:
int age = 20;
The variable is created and given an initial value.

4. Changing the Value
int age = 20;
age = 21;
Initially:
age = 20
After assignment:
age = 21
So, a variable's value can change.

5. Rules for Naming Variables
✅ Can contain:
Letters (A-Z, a-z)
Digits (0-9)
Underscore (_)
❌ Cannot:
Start with a digit
Contain spaces
Use C keywords
Use special symbols like @, #, $
Examples:
int age;          // valid
int student_name; // valid
int marks1;       // valid
int 1marks;       // invalid
int student name; // invalid

6. Important Point
C is case-sensitive.
int age;
int Age;
int AGE;
These are three different variables.

7. Example Program
#include <stdio.h>
int main()
{
    int age = 20;
    float marks = 85.5;
    char grade = 'A';

    printf("%d\n", age);
    printf("%f\n", marks);
    printf("%c\n", grade);

    return 0;
}

Remember for Notes ⭐
Variable = Name + Memory Location + Value + Data Type
