# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
```
Step1: Start
 
Step2: Create a class and declare two variable with string datatype

Step3: Loop over the entire string and reverse it

Step4: Use if condition to check whether the string and the reversed string is equal or not

Step5: print palindrome if it's equal else print not a palindrome.

Step6: stop


```

## Program:
```
using System;
namespace palindrome
{
    class Program
    {
        static void Main(string[] args)
        {
            string s, revs = "";
            Console.WriteLine(" Enter string");
            s = Console.ReadLine();
            s=s.ToLower();
            for (int i = s.Length - 1; i >= 0; i--)
            {
                revs += s[i];
            }
            if (revs == s)
            {
                Console.WriteLine("{0} is Palindrome", s);
            }
            else
            {
                Console.WriteLine("{0} is not Palindrome", s);
            }
        }
    }
}
```

## Output:


![image](https://user-images.githubusercontent.com/94165326/225877988-de8dffc3-04f6-43a8-99fa-33edfd19cec0.png)


![image](https://user-images.githubusercontent.com/94165326/225876231-097fa192-5f0e-4f0e-be66-cfc8cacb34dd.png)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
