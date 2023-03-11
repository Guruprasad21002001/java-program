# java-program
# 1. Java program to print the sum, multiply, subtract, divide and remainder of two numbers:
//Java program to print the sum, multiply, subtract, divide and remainder of two numbers
~~~
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
~~~
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

