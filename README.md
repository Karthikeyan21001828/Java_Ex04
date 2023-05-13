# Exp-4 Java program to print the even numbers between 1-20
## AIM:
to write a java program to print the even numbers between 1-20
## PROCEDURE:
### STEP 1:
Import the required packages
### STEP 2:
Get the start and end value for the even numbers to be printed.
### STEP 3:
Display the even numbers using loop.
### STEP 4:
Stop the execution.
## PROGRAM:
```java
import java.util.*;
public class EvenNumbers {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.print("Enter start and stop value: ");
        int start=sc.nextInt();
        int end=sc.nextInt();
        System.out.print("Even numbers between "+start+" and "+end+" is ");
        for(int i=start+2;i<end;i+=2)
        {
            System.out.print(i+" ");
        }

    }
}
```
## OUTPUT:
![image](https://github.com/Karthikeyan21001828/Java_Ex04/assets/93427303/df6049b3-2df7-4336-8faf-b3e265cc1a5c)
## RESULT:
A java program to print the even numbers between 1-20 has been executed successfully.
