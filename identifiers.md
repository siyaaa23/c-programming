IDENTIFIERS IN C==

An identifier is a name given by the programmer to identify program elements such as variables, functions, arrays, structures, etc.

Example
int age;
float marks;
void display()
{
    // function
}

Here:
age →     identifier
marks →   identifier
display → identifier
int →     keyword, not an identifier


2. Rules for Naming Identifiers
An identifier can contain letters, digits, and underscore (_).
It must not start with a digit.
It can start with a letter or underscore.
Spaces are not allowed.
Special characters such as @, #, $, % are not allowed.
Keywords cannot be used as identifiers.
C identifiers are case-sensitive.


***Valid Identifiers
  age
  marks
  student_name
  total1
  _number

***Invalid Identifiers
1student       // starts with a digit
student name   // contains space
student-name   // contains -
float          // keyword
marks@         // special character


3. Case Sensitivity
C is case-sensitive, so:
int age;
int Age;
int AGE;
These are treated as three different identifiers.

4. Keywords vs Identifiers
Keyword	Identifier
Reserved by C	Defined by programmer
Has predefined meaning	Used to name program elements
Cannot be used as an identifier	Can be chosen by programmer
Example: int, if, return	Example: age, marks, total
Example
int marks = 90;

Here:
int → Keyword
marks → Identifier
90 → Integer constant

⭐ Easy way to remember
Keyword   → C gives the name/meaning
Identifier → Programmer gives the name
