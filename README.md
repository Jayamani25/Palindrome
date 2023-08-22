# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
Step 1:

Create a class and declare two string variables.

Step 2:

Get the input from the user.

Step 3:

Find the length of the string using length() function;

Step 4:

Use any loop and acces the string in reverse order.

Step 5:

Store the reverse string in a new variable.

Step 6:

Compare the original string and the reversed string using conditional statement.

## Program:
Developed By: Jayamani.R
Reg no: 212222100014
```C#
using System;

public class Class1
{
    static void Main(String[] args)
    {
        string str1, str2 ="";
        Console.Write("Enter the string :");
        str1 = Console.ReadLine();
        str1 = str1.ToLower();
        for (int i = str1.Length - 1; i >= 0; i--)
        {
            str2 += str1[i];
        }
        if(str1==str2)
        {
            Console.WriteLine("Given String is Palindrome");
        }
        else
        {
            Console.WriteLine("Given String is not a Palindrome");
        }
    }
}

```

## Output:
![image](https://github.com/Jayamani25/Palindrome/assets/85949888/1ec6fd64-3cca-4790-ae4f-1193ce301ab7)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
