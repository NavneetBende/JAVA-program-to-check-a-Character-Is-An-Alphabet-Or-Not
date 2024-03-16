Checking whether a Character is Alphabet or Not?
Here, in this page we will discuss program to check whether a Character Is An Alphabet Or Not in C. In C programming language a char type variable can store many different types of characters. Here we will see how to identify whether a character is alphabet or not using C programming language

Character is alphabet or not in C
While loop in C
Explanation
In C programming language a char type variable can store many different types of characters-

Alphabets (a, b, c… )
Digits(1, 2, 3…)
Special characters(@, %, &…)
These characters are differentiated on the basis of ASCII values :

between 65 and 90 for upper case(A, B, C…)
between 97 and 122 for lower case(a, b, c…)
In here we will see how to identify whether a character is alphabet or not using C++ programming language.

Working
Get user input
Check if input is between ‘A'(65) – ‘Z'(90) or between ‘a'(96) – ‘z'(122)
If True print ‘Yes’
If False print ‘No’

C code (method 1)
Run
//C Program to find character is alphabet or not

#include <stdio.h>
int main()
{
    char ch='9';

 
    if( (ch>='a' && ch<='z') || (ch>='A' && ch<='Z'))
        printf("The inserted character %c is an Alphabet", ch);
   
    else
        printf("The entered character %c is not an Alphabet", ch);

    return 0;
}
Output
The entered character 9 is not an Alphabet
You can also check the alphabet using the ASCII values of characters like this:
if((ch >= 97 && ch <= 122) || (ch >= 65 && ch <= 90))
    printf("The entered character %c is an Alphabet",ch);
else
    printf("The entered character %c is not an Alphabet",ch);
C code (method 2)
Run
//C Program to find character is alphabet or not

#include <stdio.h>
int main()
{
   char ch='k';

      
 
  if( (ch>=97 && ch<=122) || (ch>=65 && ch<=90))
     printf("The inserted character %c is an Alphabet", ch);
   
  else
    printf("The entered character %c is not an Alphabet", ch);
  return 0;
}
Output
The entered character k is an Alphabet
