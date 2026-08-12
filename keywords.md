Keywords in C=====

Keywords are reserved words in the C programming language that have a predefined meaning.
The meaning of a keyword is already defined by the C language, so we cannot use keywords as identifiers such as variable names, function names, etc.
Example:
int age;
Here, int is a keyword, while age is an identifier.

2. Important Properties
Keywords have a special meaning in C.
They are reserved by the C language.
They cannot be used as variable or function names.
C keywords are written in lowercase.
The number of keywords depends on the C standard. For C90, there are 32 keywords.

4. C Keywords — C90
Keyword	Purpose
auto===	    Declares an automatic local variable
break==	    Terminates a loop or switch
case===     Defines a case in switch
char===	    Character data type
const===	  Declares a value that should not be modified through that identifier
continue===	Skips the current loop iteration
default===  Default case in switch
do===       Used for do-while loop
double===	  Double-precision floating-point type
else===	    Alternative block of an if statement
enum===	    Defines an enumeration
extern===  	Declares an externally defined variable/function
float===	  Floating-point data type
for===	    Used for for loop
goto===	    Transfers control to a labelled statement
if===	      Conditional statement
int===      Integer data type
long===	    Long integer/type modifier
register===	Suggests storing a variable in a CPU register
return===	  Returns control from a function
short===	  Short integer/type modifier
signed===	  Specifies signed integer type
sizeof===	  Gives the size of a type or object
static===	  Gives static storage duration / internal linkage depending on context
struct===   Defines a structure
switch===   Multi-way selection statement
typedef===	Creates a type alias
union===  	Defines a union
unsigned=== Specifies an unsigned integer type
void===	    Represents no value/type
volatile===	Indicates that a value may change unexpectedly
while=====	Used for while loop

6. Example
#include <stdio.h>

int main()
{
    int age = 20;

  if(age >= 18)
    {
        printf("Adult");
    }

  return 0;
}



Here:
int → keyword
if → keyword
return → keyword
main → not a keyword
age → identifier
printf → library function


⭐ Remember
Keyword → Reserved word with predefined meaning
Identifier → Name given by programmer

Example:
int marks;
int → Keyword
marks → Identifier
