A constant is a fixed value that does not change during the execution of a program.

Example:
int age = 20;
Here, 20 is a constant value.
Another example:
float pi = 3.14;
char grade = 'A';
Here:
20 → integer constant
3.14 → floating-point constant
'A' → character constant

2. Classification of Constants in C
Constants are broadly classified into:
Constants
│
├── Primary Constants
│   ├── Integer constants
│   ├── Real/Floating-point constants
│   └── Character constants
│
└── Secondary Constants
    ├── Array
    ├── String
    ├── Structure
    ├── Union
    ├── Pointer
    └── Enumeration

Note: This is the traditional classification commonly used in C fundamentals.

3. Primary Constants
Primary constants are the basic/simple types of constants.
A. Integer Constants
Integer constants are whole numbers without a decimal point.
Examples:
10
25
-50
0

They can also be represented in different number systems:
10      // Decimal
012     // Octal
0xA     // Hexadecimal
B. Real / Floating-Point Constants

These represent numbers containing a decimal point.
Examples:
3.14
10.5
-2.75
0.5

Scientific notation can also be used:
2.5e3
which means:
2.5 × 10³ = 2500

C. Character Constants
A character constant represents a single character and is enclosed in single quotes.
Examples:
'A'
'b'
'7'
'#'
Example:
char grade = 'A';
⚠️ 'A' is a character constant, while "A" is a string.

4. Secondary Constants
Secondary constants are formed using or combining basic data types.
A. Array
An array stores multiple values of the same type.
Example:
int marks[5] = {80, 75, 90, 85, 95};

B. String
A string is a sequence of characters enclosed in double quotes.
Example:
"Hello"
"Welcome"
"C Programming"
char name[] = "Pavani";

C. Structure
A structure groups different types of data under one name.
Example:
struct Student
{
    int age;
    float marks;
};

D. Union
A union is similar to a structure, but its members share the same memory location.
Example:
union Data
{
    int age;
    float marks;
};

E. Pointer
A pointer stores the address of another variable.
Example:
int age = 20;
int *p = &age;
Here, p is a pointer.

F. Enumeration
An enumeration (enum) defines a set of named integer constants.
Example:
enum Day
{
    MON,
    TUE,
    WED
};
Here, MON, TUE, and WED are enumeration constants.

⭐ Short Notes
  Category	Types	Example
 ** Primary Constants	Integer	10, -5
  	Real	3.14, 2.5
  	Character	'A', '7'
  **Secondary Constants	Array	int a[5]
  	String	"Hello"
  	Structure	struct Student
  	Union	union Data
  	Pointer	int *p
  	Enumeration	enum Day
    
  Easy way to remember:
  Primary → Basic values
  Secondary → Collections / derived or user-defined forms.
