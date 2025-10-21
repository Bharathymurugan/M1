<img width="1550" height="876" alt="Screenshot 2025-10-21 153626" src="https://github.com/user-attachments/assets/4c30c00e-c37c-4c24-b84b-0ad89d557899" />
# EX-01-Datatypes-Operators
## AIM:
Write a program to initialize the value as 20 & display the value.
## ALGORITHM:
1.	Declare three character variables to store the input characters.
2.	Use the scanf function to read the characters one by one from the user.
3.	Print the characters in reverse order using the printf function.
4.	End the program.

## PROGRAM:
#include <stdio.h>
int main()
{
    printf("20");
    return 0;
}

## OUTPUT:

<img width="1212" height="795" alt="Screenshot 2025-10-21 152802" src="https://github.com/user-attachments/assets/c9f18d23-ea92-4bab-9553-23e22cb9d9bb" />
















## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read a, b value and find the greatest value using  if-else
# ALGORITHM:
1.	Declare a variable to store the input value A.
2.	Use the scanf function to read the value of A from the user.
3.	Check if the value of A is greater than zero.
4.	If A is greater than zero, print a message indicating that it's a positive number. 
5.	Otherwise, print a message indicating that it's not a positive number.
6.End the program.

# PROGRAM:
#include <stdio.h>
int main ()
{
    int a,b;
    scanf("%d%d", &a,&b);
    if(a>b)
    printf("A is greatest.");
    else
    printf("B is greatest.");
    return 0;
    
}

# OUTPUT:
<img width="1518" height="873" alt="Screenshot 2025-10-21 153050" src="https://github.com/user-attachments/assets/a2234870-0ec6-4af8-b081-bab2764977fd" />











# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a C program to find number of years based on principle, rate & simple interest.



## ALGORITHM:
1.	Declare variables to store the two fraction numbers and the result.
2.	Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.	Use the scanf function to read the numerator and denominator of the first fraction.
4.	Repeat steps 2 and 3 to get the second fraction from the user.
5.	Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.	Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.	Print the minimum value.

## PROGRAM:
#include<stdio.h>
int main()
{
    float p,r,si,y;
    scanf("%f %f %f", &p,&r,&si);
    y=(si*100)/(p*r);
    printf("No.of.Year is = %.2f",y);
    return 0;
}

## OUTPUT:

<img width="1512" height="875" alt="Screenshot 2025-10-21 153232" src="https://github.com/user-attachments/assets/746a4637-e2f0-4561-827b-f9215d375fe6" />








## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to read a, b values and check whether  a greater than b. 
## ALGORITHM:
1.	Declare a variable to store the input value.
2.	Use the scanf function to read the input value from the user.
3.	Use an if statement to check if the input value is equal to 1.
4.	If the condition in the if statement is true, print a message indicating that the input value is equal to 1.
5.	Otherwise, print a message indicating that it's not equal to 1.
6.	End the program.

## PROGRAM:
#include <stdio.h>
int main()
{
    int a,b;
    scanf("%d%d", &a, &b);
    if(a>b)
    printf("a is greater than b");
    
 return 0;   
}

## OUTPUT:
<img width="1491" height="878" alt="Screenshot 2025-10-21 153431" src="https://github.com/user-attachments/assets/f9efdc17-b7bf-49a9-85a5-c865a9080a4d" />










	

## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
Write a C program to calculate total, average and percentage of 4 subjects for engineering admission.
## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:
#include <stdio.h>
int main()
{
    int eng,mat,phy,che;
    float tot, avg, per;
    scanf("%d %d %d %d", &eng, &mat, &phy, &che);
    tot=(eng+mat+phy+che);
    avg=(tot/4);
    per=avg*100/100;
    printf("Total marks = %.2f", tot);
    printf("\nAverage marks = %.2f", avg);
    printf("\nPercentage = %.2f", per);
    return 0;
}

## OUTPUT:
<img width="1550" height="876" alt="Screenshot 2025-10-21 153626" src="https://github.com/user-attachments/assets/959b9309-7880-4b0a-8360-713f8e58965c" />


## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

