# <p align="center">EXP-2-Java-program-to-compare-two-numbers...</p>

## AIM:

To write a java program to compare two numbers.

## ALGORITHM:

### Step 1:

Import the necessary packages.

### Step 2:

Get the two values from the user.

### Step 3:

Compare the two numbers using if else statements conditions.

### Step 4:

Print the result.

### Step 5:

End the program.

## PROGRAM:

```java

Name : Anto Richard. S
Register Number : 212221240005
Java program to compare two numbers.

```

```java

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

```

## OUTPUT:

![o2](https://github.com/anto-richard/EXP-2-Java-program-to-compare-two-numbers/assets/93427534/594dce5d-7695-41da-b7ca-787beeaf1916)

## RESULT:

Thus the java program to compare two numbers is written and implemented successfully.

