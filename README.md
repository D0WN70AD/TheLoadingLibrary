# TheLoadingLibrary

## Before you continue
Please keep in mind that this is my first project published here and if I did anything wrong, let me know.

## Description
 The Loading Library aims to make programming in c# easier.
 
## What does it do?
This library currently has 8 functions:<br />
<br /> LoadingLibrary.SumTwoNumbers();
<br /> LoadingLibrary.SubtractTwoNumbers();
<br /> LoadingLibrary.MultiplyTwoNumbers();
<br /> LoadingLibrary.DivideTwoNumbers();
<br /> LoadingLibrary.GenerateRandomNumber();
<br /> LoadingLibrary.CreateRandomPassword();
<br /> LoadingLibrary.DoubleToInt();
<br /> LoadingLibrary.GetIPAddress(out IP);

## SumTwoNumbers()
It's self-explanatory, it sums two integers.
An example of how to use it is:
``` LoadingLibrary.SumTwoNumbers(firstNumber, secondNumber, out result);  ```
<br /> Where firstNumber and secondNumber are integers and result is the variable in which the result is stored.
<br /> Example: ``` LoadingLibrary.SumTwoNumbers(a, b, out sum); ```

## SubtractTwoNumbers()
It's self-explanatory, it subtracts two integers.
An example of how to use it is:
``` LoadingLibrary.SubtractTwoNumbers(firstNumber, secondNumber, out result);  ```
<br /> Where firstNumber and secondNumber are integers and result is the variable in which the result is stored.
<br /> Example: ``` LoadingLibrary.SubtractTwoNumbers(a, b, out subtraction); ```

## MultiplyTwoNumbers()
It's self-explanatory, it multiplies two integers.
An example of how to use it is:
``` LoadingLibrary.MultiplyTwoNumbers(firstNumber, secondNumber, out result);  ```
<br /> Where firstNumber and secondNumber are integers and result is the variable in which the result is stored.
<br /> Example: ``` LoadingLibrary.MultiplyTwoNumbers(a, b, out multiplication); ```

## DivideTwoNumbers()
It's self-explanatory, it divides two integers.
An example of how to use it is:
``` LoadingLibrary.MultiplyTwoNumbers(firstNumber, secondNumber, out result);  ```
<br /> Where firstNumber and secondNumber are integers, firstNumber being the first number and secondNumber being the second number(if firstNumber = 4 and secondNumber = 2, then the result will be 4/2) and result is the variable in which the result is stored.
<br /> Example: ``` LoadingLibrary.DivideTwoNumbers(a, b, out division); ```

## GenerateRandomNumber()
It generates a random number between two numbers provided by the user.
An example of how to use it is:
``` LoadingLibrary.GenerateRandomNumber(50, 100, out result);  ```
<br /> Where 50 is the minimum value that can be generated and 100 is the maximum value that can be generated, and result is the variable in which the generated number is stored. 
<br /> The generated number and the numbers between which the random number is generated must be integers.
<br /> Example: ``` LoadingLibrary.GenerateRandomNumber(50, 100, out result); ```
<br /> or ``` LoadingLibrary.GenerateRandomNumber(a, b, out result); ```

## CreateRandomPassword()
It generates a random password of the length specified by the user.
An example of how to use it is:
``` LoadingLibrary.CreateRandomPassword(10, out pass);  ```
<br /> Where 10 is the length of the password, and result is the variable in which the generated password is stored. 
<br /> Example: ``` LoadingLibrary.CreateRandomPassword(10, out pass); ```
<br /> or ``` LoadingLibrary.CreateRandomPassword(num, out pass); ```

## DoubleToInt()
It converts a double to an int.
An example of how to use it is:
``` LoadingLibrary.DoubleToInt(29.7431238472, out result);  ```
<br /> Where 29.7431238472 is the double that needs to be converted, and result is the variable in which the int is stored (In our case it will be 30). 
<br /> Example: ``` LoadingLibrary.DoubleToInt(29.7431238472, out myint); ```
<br /> or ``` LoadingLibrary.CreateRandomPassword(mydouble, out myint); ```

## GetIpAddress()
It gets the IP address of the machine that the program is run on.
An example of how to use it is:
``` LoadingLibrary.GetIPAddress(out IP);  ```
<br /> Where IP is the string variable in which the IP is stored. 
<br /> Example: ``` LoadingLibrary.GetIPAddress(out IP); ```
