# java-program
# 1. Java program to print the sum, multiply, subtract, divide and remainder of two numbers:
//Java program to print the sum, multiply, subtract, divide and remainder of two numbers
~~~java
import java.util.*;
public class ArithmeticOperations
{
    public static void main(String[] args)
    {
        Scanner s = new Scanner(System.in);
        int a,b;
        System.out.print("Enter your first number: ");
        a = s.nextInt();
        System.out.print("Enter your second number: ");
        b = s.nextInt();

        int sum = a+b;
        int sub = a-b;
        int multiply = a*b;
        int divide = a/b;
        int rem = a%b;

        System.out.println("Sum of two numbers : "+sum);
        System.out.println("Difference of two numbers : "+sub);
        System.out.println("Product of two numbers : "+multiply);
        System.out.println("Quotient of two numbers : "+divide);
        System.out.println("Remainder of two numbers : "+rem);
    }
}
~~~
Program and Output screenshots:

![prog1](https://user-images.githubusercontent.com/95342910/224466142-b37445ba-62d6-46e2-b506-231a5eaca67b.png)

![out1](https://user-images.githubusercontent.com/95342910/224466163-22d53f26-29be-416f-aca6-aba9966a1215.png)


# 2. Java program to compare two numbers:
// Java program to compare two numbers...
~~~java
import java.util.*;
public class CompareNumber
{
    public static void main(String[] args)
    {
        Scanner s = new Scanner(System.in);
        int x,y;

        System.out.print("Enter the first number to compare: ");
        x = s.nextInt();
        System.out.print("Enter the second number to compare: ");
        y = s.nextInt();

        if (x > y)
        {
            System.out.println(x + " is greater than " + y);
        } else if (x < y)
        {
            System.out.println(x + " is less than " + y);
        } else
        {
            System.out.println(x + " is equal to " + y);
        }
    }
}
~~~
Program and Output screenshots:

![prog2](https://user-images.githubusercontent.com/95342910/224466264-b341a80d-ea73-4177-9cb3-1514132f367f.png)

![out2](https://user-images.githubusercontent.com/95342910/224466271-4a951c19-c454-481f-b2fb-f876aecd3134.png)

# 3. Java program to convert a string to an integer:
// Java program to convert a string to an integer.....
~~~java
import java.util.*;

public class Str {
    public static void main(String[] args)
    {
        Scanner s = new Scanner(System.in);
        System.out.print("Enter an string: ");

        if(s.hasNextInt())
        {
            int n = s.nextInt();
            System.out.println("The integer value is " + n);
        } else
        {
            System.out.println("Invalid input, please enter an integer.");
        }
    }
}
~~~
Program and Output screenshots:

![prog3](https://user-images.githubusercontent.com/95342910/224466398-2d84fa92-db90-4e9d-99de-b56e0bbc9264.png)

![out3](https://user-images.githubusercontent.com/95342910/224466433-f051f3db-7118-4ba5-9e3c-ed333d36cc5a.png)

# 4. Java Program to find area of rhombus:

//Java Program to find area of rhombus..
~~~java
import java.util.*;
public class RhombusArea
{
    public static void main(String[] args)
    {
        Scanner s = new Scanner(System.in);
        System.out.print("Enter the length of the diagonal 1: ");
        int x = s.nextInt();
        System.out.print("Enter the length of the diagonal 2: ");
        int y = s.nextInt();

        int area =(x * y)/2;
        System.out.println("The area of the rhombus is " + area);
    }
}
~~~
Program and Output screenshots:

![prog4](https://user-images.githubusercontent.com/95342910/224467162-5ae90b5e-34ea-4843-bf5f-f07d54f632f7.png)

![out4](https://user-images.githubusercontent.com/95342910/224467178-55828e35-dc05-463f-80c9-a965531adc32.png)

#5. Java program to find the number of days in a month:
// Java program to find the number of days in a month...
~~~java
import java.util.*;
public class MonthDays {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        System.out.print("Enter a month from (1-12): ");
        int month = s.nextInt();

        switch (month) {
            case 1:
                System.out.println("January has 31 days");
                break;
            case 2:
                System.out.print("Enter a year: ");
                int year = s.nextInt();
                int days;
                if ((year % 4 == 0 && year % 100 != 0) || year % 400 == 0) {
                    days = 29;
                } else {
                    days = 28;
                }
                System.out.println("February has " + days + " days");
                break;
            case 3:
                System.out.println("March has 31 days");
                break;
            case 4:
                System.out.println("April has 30 days");
                break;
            case 5:
                System.out.println("May has 31 days");
                break;
            case 6:
                System.out.println("June has 30 days");
                break;
            case 7:
                System.out.println("July has 31 days");
                break;
            case 8:
                System.out.println("August has 31 days");
                break;
            case 9:
                System.out.println("September has 30 days");
                break;
            case 10:
                System.out.println("October has 31 days");
                break;
            case 11:
                System.out.println("November has 30 days");
                break;
            case 12:
                System.out.println("December has 31 days");
                break;
            default:
                System.out.println("Invalid input, a year has only 12 months!!!");
                break;
        }
    }
}
~~~
Program and Output screenshots:

![prog5(1)](https://user-images.githubusercontent.com/95342910/224467980-2256ac2f-7d7c-41a6-82b6-dcb768ad308a.png)

![prog5(2)](https://user-images.githubusercontent.com/95342910/224467989-cf560690-78cf-493a-ada5-1caa77bc26f8.png)

![out5](https://user-images.githubusercontent.com/95342910/224467994-9b4e1190-f222-45f8-b5c0-d7d5162083ed.png)

# 6. Java program to print the even numbers from 1 to 20:
// Java program to print the even numbers from 1 to 20....
~~~java
public class EvenNumbers
{
    public static void main(String[] args)
    {
        for (int i = 1; i <= 20; i++)
        {
            if(i%2==0)
            {
                System.out.print(i+"\t");
            }
        }
    }
}
~~~
Program and Output screenshots:

![prog6](https://user-images.githubusercontent.com/95342910/224473953-9a5b6323-669e-47f8-9439-a9e1f71d6477.png)

![out6](https://user-images.githubusercontent.com/95342910/224473948-13e73802-a9c1-4a4c-b32b-f4e02473d81a.png)

#7. Java program to create a simple calculator:
// Java program to create a simple calculator...
~~~java
import java.util.Scanner;
public class Calculator {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        System.out.print("Enter the first number: ");
        int num1 = s.nextInt();
        System.out.print("Enter the second number: ");
        int num2 = s.nextInt();
        System.out.print("Enter an operator to perform 1.Addition, 2.Subtraction, 3.Multiplication, 4.Division: ");
        int option = s.nextInt();
        int result;
        switch(option){
            case 1:
                result = num1 + num2;
                System.out.println("Addition of the two numbers is : " + result);
                break;
            case 2:
                result = num1 - num2;
                System.out.println("Subtraction of the two numbers is : " + result);
                break;
            case 3:
                result = num1 * num2;
                System.out.println("Multiplication of the two numbers is : " + result);
                break;
            case 4:
                result = num1 / num2;
                System.out.println("Division of the two numbers is : " + result);
                break;
            default:
                System.out.println("Invalid operator");
        }
    }
}
~~~~
Program and Output screenshots:

![prog7](https://user-images.githubusercontent.com/95342910/224531270-0ffd6613-21cd-4707-90cb-a56e19230ca2.png)

![out7](https://user-images.githubusercontent.com/95342910/224531283-b11d9806-9b1c-4875-b58c-8a81cde6d754.png)

#8. Java program to print multiplication table of given number:
// Java program to print multiplication table of given number...
~~~java
import java.util.Scanner;
public class MultiplicationTable
{
    public static void main(String[] args)
    {
        Scanner s = new Scanner(System.in);
        System.out.print("Enter the number to print the multiplication table : ");
        int z = s.nextInt();
        for(int i=1;i<=10;i++)
        {
            System.out.println(z+" * "+i+" = "+(z*i));
        }
    }
}
~~~
Program and Output screenshots:

![prog8](https://user-images.githubusercontent.com/95342910/224531592-be8587c2-fb57-4bbf-ae91-63e09d565fbf.png)

![out8](https://user-images.githubusercontent.com/95342910/224531616-7c00265d-7450-472f-a94d-296b75f962c5.png)
