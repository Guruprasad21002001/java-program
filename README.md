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
