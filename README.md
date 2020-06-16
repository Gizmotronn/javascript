# javascript
Learning & Working with Javascript
File: https://acord.bit.ai/docs/view/rcYtrhiWFUcbmcc3

Intro to Javascript
Using for practice with 
screeps/screeps A standalone server for programming game Screeps. Contribute to screeps/screeps development by creating an account on GitHub.
javascript Learning & Working with Javascript
Console
Panel that displays important information, like errors, for developers
Much of the work the computer does with our code is invisible to us by default. If we want to see things appear on our screen, we can print, or log, to our console directly.
In JS, the console codeword refers to an object - a collection of data and actions, that we can use in our code
Keywords are words that are built in to JS (like keywords in Python)
The computer recognizes these keywords as keywords and "treats them specially"
Actions = methods in Javascript
One method built into the console object in Javascript is the .log()` method.
Writing "console.log()", what we put in the parenthesis will get printed/logged to the console
This prints "5" to the console: console.log(5); 
End each statement with a semi-colon so that you never leave one out when you need to, however you don't need to all the time
Challenge 1
js.JPG 

13th June 2020
"console.log("Hello");" prints "Hello" to the console in Javascript.
The ";" isn't needed in this case, however, it is good practice to include it for when the semicolon IS needed
Commenting
The computer will ignore the comments as the program runs
They explain (they = comments) what the code is doing, leave instructions, etc
There are two types of code comments in JavaScript:
Single Line Comment
Multi-line comment
// This is a single line comment
/* This is a multiline comment */
Here's some commenting in action (taken from the Codecademy JS Tutorial for comments):
@Gizmotronn js tutorials  
(Click on the gist to view the challenge solution).
Data Types in Python
Data types are the classifications given to different kinds of data that are used in programming. There are seven fundamental data types in Javascript:
Number: any number. Can include decimals: 1, 50409, 1.0, 504.09
String: Any grouping of characters on the keyboard
Letters
Numbers
Spaces 
Symbols
They are surrounded by either "" or ''. Single quotes are preferred
Boolean: This data type only has two possible values"
true
false
Null: Represents the intentional absence of a value
Represented by the keyword null
Symbol: A unique identifier, useful in more complex coding (we'll come back to this later)
Object: Collections of related data
The first six data types mentioned (i.e. everyone except for "Object") are called primitive data types
They're the most basic data types in the language
Objects are more complex

Challenge
Print those data types (string, numbers):
js-challenge-intro-datatypes1 @gizmotronn  

Arithmetic Operators
An operator is a character that performs a task in our code
JS has several in-built arithmetic operators; these allow us to perform mathematical calculations on numbers
Add: +
Subtract: -
Multiply: *
Challenge
console.log(3+3.5);
console.log(17 + 3.5)
console.log(2020-1969)
console.log(65/240)
console.log(0.2708*100)
String Concatenation
Operators can also be used to connect or append multiple strings:
string concatenation for js tutorials @gizmotronn pt 1  
Also can be done with:
Setting a variable and concatenating
Appending multiple strings together is called string concatenation, or just concatenation
Notice in the third example we had to make sure to include a space at the end of the first string. The computer will join the strings exactly, so we needed to make sure to include the space we wanted between the two strings.
js string concatenation part 2  
Challenge: 
js string concatenation part 3  
Properties
When a new piece of data is inserted into a Javascript program, the browser saves it as an instance of the data type. 
Every string instance has a property called Length that stores the number of characters in the string
Property information can be retrieved by appending the string with a period and the property name: 
Javascript Practice w/ @Gizmotronn (like every gist here) --> js properties w/ codecademy  
^^ The ".dot" is another operator --> period/dot operator
JS Practice w/ properties (see all gists on @IrisDroidology & @Gizmotronn as always)  
Methods
Methods are actions that we can perform (in JS)
We call or use these methods by appending instances with:
A period (dot operator)
Name of the method
Opening & closing brackets
Example:
'example string'.methodName()
console.log('Hello, World!");
^^ console + .log --> ".log" is the name of the method
We call the .log method on the "console" object
Some string methods:
methods1.js  
^^ The first line: console.log('hello'.toUpperCase()); // Prints 'HELLO'
We start it off how we did before, with "console.log();"
We add the string, 'hello', and then a method --> .toUpperCase()
This method makes the string inside all uppercase **
The second line, using the .startswith() method is fairly self-explanatory
Challenge:
methods2.js @IrisDroidology & @Gizmotronn on Github.com 
Part 2: 
In the second console.log() statement in app.js, we have a string ' Remove whitespace ' which has spaces before and after the words 'Remove whitespace'. If we browse the JavaScript string documentation, we find several built-in string methods that each accomplish a different goal. The one method that seems ideal for us is .trim().Use the method to remove the whitespace at the beginning and end of the string in the second console.log() statement.
Built-in objects
