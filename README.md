PPS – Operators Program (Unit 2)

1) Arithmetic Operators

#include <stdio.h>

int main() {

    int a = 10;
    int b = 20;

    printf("Addition = %d\n", a + b);
    printf("Subtraction = %d\n", a - b);
    printf("Multiplication = %d\n", a * b);
    printf("Division = %d\n", a / b);

    return 0;
}

Output:
Addition = 30
Subtraction = -10
Multiplication = 200
Division = 0


2) Relational Operators

#include <stdio.h>

int main() {

    int a = 9, b = 10;

    printf("a > b = %d\n", a > b);
    printf("a < b = %d\n", a < b);
    printf("a >= b = %d\n", a >= b);

    return 0;
}

Output:
a > b = 0
a < b = 1
a >= b = 0


3) Logical Operators

#include <stdio.h>

int main() {

    int x = 10, z = 6;

    printf("AND = %d\n", (x > z && z < 5));
    printf("OR = %d\n", (x > 5 || z > 10));

    return 0;
}

Output:
AND = 0
OR = 1


Notes (simple):
Arithmetic = calculation
Relational = compare (1 or 0)
Logical = multiple condition check

True = 1
False = 0


Increment and Decrement Operators (Unit 2)

#include <stdio.h>

int main() {

    int a = 5;

    printf("Initial value = %d\n", a);

    printf("Post Increment = %d\n", a++);   // use first then increase
    printf("After Post Increment = %d\n", a);

    printf("Pre Increment = %d\n", ++a);    // increase first then use

    printf("Post Decrement = %d\n", a--);   // use first then decrease
    printf("After Post Decrement = %d\n", a);

    printf("Pre Decrement = %d\n", --a);    // decrease first then use

    return 0;
}

Bitwise Operators (Unit 2)

#include <stdio.h>

int main() {

    int a = 5;   // 101
    int b = 3;   // 011

    printf("a & b = %d\n", a & b);   // AND
    printf("a | b = %d\n", a | b);   // OR
    printf("a ^ b = %d\n", a ^ b);   // XOR
    printf("~a = %d\n", ~a);         // NOT
    printf("a << 1 = %d\n", a << 1); // Left Shift
    printf("a >> 1 = %d\n", a >> 1); // Right Shift

    return 0;
}

Assignment Operators (Unit 2)

#include <stdio.h>

int main() {

    int a = 10;

    printf("Initial value = %d\n", a);

    a += 5;   // a = a + 5
    printf("a += 5 → %d\n", a);

    a -= 3;   // a = a - 3
    printf("a -= 3 → %d\n", a);

    a *= 2;   // a = a * 2
    printf("a *= 2 → %d\n", a);

    a /= 4;   // a = a / 4
    printf("a /= 4 → %d\n", a);

    a %= 3;   // a = a % 3
    printf("a %%= 3 → %d\n", a);

    return 0;
}


PPS – Unit 2 Programs  
(Expressions, Conditional, Precedence, Type Conversion)

---------------------------------------

1) Expression Program

#include <stdio.h>

int main() {

    int a = 10, b = 5, c = 2;

    int result = a + b * c;

    printf("Expression Result = %d\n", result);

    return 0;
}

Output:
Expression Result = 20


---------------------------------------

2) Precedence Program

#include <stdio.h>

int main() {

    int a = 10, b = 5, c = 2;

    int r1 = a + b * c;
    int r2 = (a + b) * c;

    printf("Without Bracket = %d\n", r1);
    printf("With Bracket = %d\n", r2);

    return 0;
}

Output:
Without Bracket = 20
With Bracket = 30


---------------------------------------

3) Conditional Expression Program

#include <stdio.h>

int main() {

    int a = 10, b = 5;

    int max = (a > b) ? a : b;

    printf("Max Value = %d\n", max);

    return 0;
}

Output:
Max Value = 10


---------------------------------------

4) Type Conversion Program

#include <stdio.h>

int main() {

    int a = 10, b = 4;
    float x = 5.5;

    float r1 = a + x;          // implicit
    float r2 = (float)a / b;   // explicit

    printf("Implicit = %.2f\n", r1);
    printf("Explicit = %.2f\n", r2);

    return 0;
}

Output:
Implicit = 15.50
Explicit = 2.50


---------------------------------------

Notes (Simple):

Expression = calculation  
Precedence = order of operation  
Conditional (?:) = shortcut of if-else  
Type conversion = data type change  

---------------------------------------

🔥 Ready for Practical + Viva + Exam

---------------------------------------
EXAM MCQ (Important)

1) 10 % 3 = ?
a) 3  b) 1  c) 0  d) 10
Answer: b

2) 5 > 3 gives?
a) 0  b) 1  c) 5  d) 3
Answer: b

3) Which operator is used for AND?
a) &  b) &&  c) ||  d) !
Answer: b

4) Output of (1 && 0)?
a) 1  b) 0  c) -1  d) error
Answer: b

5) Which is relational operator?
a) +  b) *  c) >  d) %
Answer: c


---------------------------------------
THEORY QUESTIONS (Exam)

1) Explain Arithmetic Operators with example.

2) What are Relational Operators? Explain any three.

3) Explain Logical Operators with example.

4) Difference between Relational and Logical Operators.

5) What is the use of % operator? Give example.

---------------------------------------

🔥 Ready for practical + viva + exam
