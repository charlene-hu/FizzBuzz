# FizzBuzz

This application is a simple single page application. It was written in asp.net MVC, C#, JQuery and Bootstrap.

###Assumptions
Item 4 in the specification: "At the end of the run the program should output each division that was performed", does not seem to perfectly match the sample output. Thus, the application prints two sets of result as below. The first set matches the sample output. And the second set prints out the division operation for all all divisible numbers in the collection.
```
Divided 1 by 3      Divided 1 by 3
Divided 1 by 5      Divided 1 by 5
Fizz                Divided 3 by 3
Buzz                Divided 3 by 5
Invalid Item        Divided 5 by 3
FizzBuzz            Divided 5 by 5
Invalid Item        Divided 15 by 3
Divided 23 by 3     Divided 15 by 5
Divided 23 by 5     Divided 23 by 3
                    Divided 23 by 5
```

###Specifications
```
Please write a .NET MVC Single Page Web application using the C# language that allows for the following inputs:
  
  1) A Collection of objects
  2) A lower number
  3) A higher number
  
Attempts to do the following for each object in the collection:

1)	If the object is divisible by the lower number then output the word “Fizz”
2)	If the object is divisible by the higher number then output the word “Buzz”
3)	If the object is divisible by both numbers then output the word “FizzBuzz”
4)	At the end of the run the program should output each division that was performed.  For instance 
	“Divided: 0 by: <lower number>” - <lower number> is the lower number input 
	“Divided: 0 by: <higher number>” - <higher number> is the higher number input  	
    	If the object cannot be divided then output: "Invalid Item"


Sample input:

Collection [1,3,5,,15, A, 23]
lower number = 3
higher number =5

Sample Output:
Divided 1 by 3
Divided 1 by 5
Fizz
Buzz
Invalid Item
FizzBuzz
Invalid Item
Divided 23 by 3
Divided 23 by 5
```

