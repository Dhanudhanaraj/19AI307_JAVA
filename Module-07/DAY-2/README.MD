# Ex.No:7(B) EXCEPTION HANDLING-FINALLY
## AIM:
To Write a Java program to demonstrate control flow of try-catch-finally clause when NumberFormat Exception occur in try block and handled in catch block


## ALGORITHM :
1.	Start the Program
2.	Import `java.util.*` for input handling
3.	Define class `HelloWorld`:
-	a) In `main` method, create `Scanner` object `sc` for input
4.	Use `try` block to:
-	a) Read a string `str` from user input
-	b) Convert `str` to an integer using `Integer.parseInt()` and print the result
5.	Use `catch` block to handle `NumberFormatException`:
-	a) If the string can't be converted to an integer, print the exception message
6.	Use `finally` block to:
-	a) Print "Finally block executed"
7.	After the `try-catch-finally` block, print "Outside try-catch-finally clause"
8.	End



## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Finally using Java
Developed by: DHANUMALYA D
RegisterNumber: 212222230030
*/
```

## Sourcecode.java:
```
import java.util.*;
public class A
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        try
        {
            int a=100;
            int b=sc.nextInt();
            int c=a/b;
            System.out.println("Valid Statement :"+c);
        }
        catch(ArithmeticException e)
        {
            System.out.println("Exception: "+e);
        }
        finally
        {
            System.out.println("Finally block executed");
        }
        System.out.println("Outside try-catch-finally clause");
    }
    
}
```





## OUTPUT:

![Image](https://github.com/user-attachments/assets/edd49798-40ff-4e35-b2e4-e0af5be8da75)
## RESULT:
Thus the Java program to demonstrate control flow of try-catch-finally clause when NumberFormatException occur in try block and handled in catch block was executed successfully.



