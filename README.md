# Sequence-and-File-Operations-in-Python

Assignment-1


1. Write a program which will find factors of given number and find whether the factor is even or odd.
Hint: Use Loop with if-else statements

2. Write a code which accepts a sequence of words as input and prints the words in a sequence after sorting them alphabetically.
Hint: In case of input data being supplied to the question, it should be assumed to be a console input.

3. Write a program, which will find all the numbers between 1000 and 3000 (both included) such that each digit of a number is an even number. The numbers obtained should be printed in a comma separated sequence on a single line.
Hint: In case of input data being supplied to the question, it should be assumed to be a console input. Divide each digit with 2 and verify is it even or not.

4. Write a program that accepts a sentence and calculate the number of letters and digits.
Suppose if the entered string is: Python0325
Then the output will be:
LETTERS: 6
DIGITS:4
Hint: Use built-in functions of string.

5. Design a code which will find the given number is Palindrome number or not.
Hint: Use built-in functions of string.

Assignment-2

1. What is the output of the following code? nums = set([1,1,2,3,3,3,4,4]) print(len(nums))
Hint: Set consists unique element.

2. What will be the output? d = {"john":40, "peter":45} print(list(d.keys())) Hint: d.keys() is the function which will show keys.

3. A website requires a user to input username and password to register. Write a program to check the validity of password given by user. Following are the criteria for checking password:
1. At least 1 letter between [a-z]
2. At least 1 number between [0-9]
1. At least 1 letter between [A-Z]
3. At least 1 character from [$#@]
4. Minimum length of transaction password: 6
5. Maximum length of transaction password: 12
Hint: In case of input data being supplied to the question, it should be assumed to be a console input.

4. Write a for loop that prints all elements of a list and their position in the list.
a = [4,7,3,2,5,9]
Hint: Use Loop to iterate through list elements.
Module 2 - Sequence and File Operations


5. Please write a program which accepts a string from console and print the characters that have even indexes.
Example: If the following string is given as input to the program:
H1e2l3l4o5w6o7r8l9d
Then, the output of the program should be:
Helloworld

6. Please write a program which accepts a string from console and print it in reverse order.
Example: If the following string is given as input to the program:
rise to vote sir
Then, the output of the program should be:
ris etov ot esir

7. Please write a program which count and print the numbers of each character in a string input by console.
Example: If the following string is given as input to the program:
abcdefgabc
Then, the output of the program should be:
a,2
c,2
b,2
e,1
d,1
g,1
f,1

8. With two given lists [1,3,6,78,35,55] and [12,24,35,24,88,120,155], write a program to make a list whose elements are intersection of the above given lists.
Module 2 - Sequence and File Operations

9. By using list comprehension, please write a program to print the list after removing the value 24 in [12,24,35,24,88,120,155].

10. By using list comprehension, please write a program to print the list after removing the 0th,4th,5th numbers in [12,24,35,70,88,120,155].

11. By using list comprehension, please write a program to print the list after removing delete numbers which are divisible by 5 and 7 in [12,24,35,70,88,120,155].

12. Write a program to compute 1/2+2/3+3/4+...+n/n+1 with a given n input by console (n>0).
Example:
If the following n is given as input to the program:
5
Then, the output of the program should be:
3.55

Assignment-3

Domain – Telecom
focus – Optimization
Business challenge/requirement
LifeTel Telecom is the latest entrant in the highly competitive Telecom market of Singapore. It issues SIM to the verified users. Till now verification was manual through the photocopy of approved id card document. However, government has recently introduced Social ID called Reference ID which is mapped to fingerprint of user. LifeTel should now verify user against the fingerprint and Reference ID

Key issues:
Build a system where when user enters Reference ID it is encrypted, so that hackers cannot view the mapping of Reference ID and finger print
