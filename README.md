# javascript
Learning & Working with Javascript
File: https://acord.bit.ai/docs/view/rcYtrhiWFUcbmcc3

<details>
<summary>How do I dropdown?</summary>
<br>
This is how you dropdown.
<br><br>
<pre>
&lt;details&gt;
&lt;summary&gt;How do I dropdown?&lt;&#47;summary&gt;
&lt;br&gt;
This is how you dropdown.
&lt;&#47;details&gt;
</pre>
</details>

---

<details open>
<summary>Want to ruin the surprise?</summary>
<br>
Well, you asked for it!
<br><br>
<pre>
&lt;details open&gt;
&lt;summary&gt;Want to ruin the surprise?&lt;&#47;summary&gt;
&lt;br&gt;
Well, you asked for it!
&lt;&#47;details&gt;
</pre>
</details>


# Intro to Javascript
Using for practice with 
screeps/screeps A standalone server for programming game Screeps. Contribute to screeps/screeps development by creating an account on GitHub.

## Console
Panel that displays important information, like errors, for developers
Much of the work the computer does with our code is invisible to us by default. If we want to see things appear on our screen, we can print, or log, to our console directly.
In JS, the console codeword refers to an object - a collection of data and actions, that we can use in our code
Keywords are words that are built in to JS (like keywords in Python)
The computer recognizes these keywords as keywords and "treats them specially"
Actions = methods in Javascript
One method built into the console object in Javascript is the .log() method.
Writing "console.log()", what we put in the parenthesis will get printed/logged to the console
This prints "5" to the console: console.log(5); 
End each statement with a semi-colon so that you never leave one out when you need to, however you don't need to all the time
Challenge 1
js.JPG 

## 13th June 2020
"console.log("Hello");" prints "Hello" to the console in Javascript.
The ";" isn't needed in this case, however, it is good practice to include it for when the semicolon IS needed
Commenting
The computer will ignore the comments as the program runs
They explain (they = comments) what the code is doing, leave instructions, etc
There are two types of code comments in JavaScript:
```js
// This is a single line comment
/* This is a multiline comment */
```
Here's some commenting in action (taken from the Codecademy JS Tutorial for comments):
```js
console.log('It was love at first sight.');

console.log('The first time Yossarian saw the chaplain he fell madly in love with him.');
console.log('Yossarian was in the hospital with a pain in his liver that fell just short of being jaundice.');
console.log('The doctors were puzzled by the fact that it wasn\'t quite jaundice.');
console.log('If it became jaundice they could treat it.');
console.log('If it didn\'t become jaundice and went away they could discharge him.');
console.log('But this just being short of jaundice all the time confused them.');
```

## Data Types in Python
Data types are the classifications given to different kinds of data that are used in programming.
There are seven fundamental data types in Javascript:
* Number: any number. Can include decimals: 1, 50409, 1.0, 504.09
* String: Any grouping of characters on the keyboard
  * They are surrounded by either "" or ''. Single quotes are preferred
* Letters
* Numbers
* Spaces 
* Symbols
  * Symbol: A unique identifier, useful in more complex coding (we'll come back to this later)
* Boolean: This data type only has two possible values
  * true
  * false
* Null: Represents the intentional absence of a value
  * Represented by the keyword null
* Object: Collections of related data

The first six data types mentioned (i.e. everyone except for "Object") are called primitive data types.
* They're the most basic data types in the language.
* Objects are more complex.

### Challenge
Print those data types (string, numbers):
js-challenge-intro-datatypes1 @gizmotronn  
```js
console.log('JavaScript');
console.log(2011)
console.log('Woohoo! I love to code! #codecademy')
console.log(20.49);
```

## Arithmetic Operators
### Challenge
```js
console.log(17 + 3.5)
console.log(2020-1969)
console.log(65/240)
console.log(0.2708*100)
```
Rest of it is on bit.ai


# Intro to Variables
## Creating variables
There were a lot of changes introduced in the ES6 version of Javascript in 2015.
One of the biggest changes was the introduction of two new keywords, let and const
These create/declare variables
Before this version, programmers could only use the var keyword to declare variables
Creating a variable called myName with the value Arya:

var myName = 'Arya';
console.log(myName); // Printing, or outputting it to the console
// Output: Arya
var is short for variable
It is a Javascript keyword that creates/declares a new variable
  2. myName is the variable's name
	 a. This capitilization is called camel casing
  3. = is the assignment operator
	 a. It assings the value 'Ayra' to the variable myName 
  4. 'Arya' is the value assigned (=) to the variable myName 
	 b. The myName variable is initialized with the value of 'Arya 
  5. After the variable is declared, the string value is printed to the console by referencing 		       the variable name: console.log(myName); 

Rules when naming variables
Variable names cannot start with numbers
Variable names are case sensitive
Variable names cannot be the same as keywords

Challenge
Declare a variable named favoriteFood using the var keyword and assign to it the string pizza
var favoriteFood = 'pizza";

Declare a variable named numOfSlices using the var keyword and assign to it the number 8
var numOfSlices = 8;

> Using the numOfSlices variable, use `console.log()` to print the value saved to `favoriteFood`
> On the following line, use `console.log()` to print the value saved to `numOfSlices`:
```js
console.log(favoriteFood);
console.log(numOfSlices);
```

Check out https://acord.software/stellarios/starsailors#!/javascript:introduction-to-javascript/ive-started-discussing-it

# Creating variables using `let`
<iframe class="clickup-embed clickup-dynamic-height" src="https://doc.clickup.com/d/h/6jy6k-275/" frameborder="0" onmousewheel="" width="100%" height="100%" style="background: transparent; border: 1px solid #ccc;"></iframe><script async src="https://app-cdn.clickup.com/assets/js/forms-embed/v1.js"></script>

# Creating variables using `const`
<iframe class="clickup-embed clickup-dynamic-height" src="https://doc.clickup.com/d/h/6jy6k-296/e71bd5ee4886121" frameborder="0" onmousewheel="" width="100%" height="100%" style="background: transparent; border: 1px solid #ccc;"></iframe><script async src="https://app-cdn.clickup.com/assets/js/forms-embed/v1.js"></script> <!--https://doc.clickup.com/d/h/6jy6k-296/e71bd5ee4886121-->

# Increment & Decrement Operator
https://doc.clickup.com/d/h/6jy6k-331/d9caa2071b4ed3c

<iframe class="clickup-embed clickup-dynamic-height" src="https://doc.clickup.com/d/h/6jy6k-331/d9caa2071b4ed3c" frameborder="0" onmousewheel="" width="100%" height="100%" style="background: transparent; border: 1px solid #ccc;"></iframe><script async src="https://app-cdn.clickup.com/assets/js/forms-embed/v1.js"></script>
