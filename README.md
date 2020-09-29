VARIABLES PRACTICE
==================

![](https://media.giphy.com/media/fXtGlVSI2ZB2E1JO0b/giphy.gif)

Today we are going to get practice (1) creating, (2) updating, and (3) printing our very own variables. **Variables** are a placeholder for a piece of information that can change. To create a variable we use the word `var` followed by the name of the variable. You can give a variable *almost* any name so long as it is
1. A single word
2. Does not begin with a number
3. Does not contain punctuation

VARIABLES: THE BASICS
---------------------
Here is an example of how some variables are intialized
```javascript
//Initialize a variable and give it a value all on a single line.
var total = 10;
//Increase total by 1
total = total + 1;
//Initialize a variable without a value.
var myNextVariable;
//Update the variable with a new value
myNextVariable = "Hello World";
var truthy = true;
var stringy = "Text goes in between quotes";
```

Variables can store integers, floats (decimal numbers), strings, or boolean (true/false) values. Additionally, you can store the output of mathematical operations (like the example with `total` above. The basic math operators for JavaScript are: 

Operation | Symbol|
------------ | -------------
Add| `+` | 
Subtract | `-`|
Multiply | `*`|
Divide | `/`| 
Exponent | `**`|

CONCATENATION
-------------
Often we want to print out a variable as part of a longer string. For example, suppose we stored the users name in a variable and we wanted to print out the message "Hello yourName!". We can use **concatenation** in order to join together strings with the values we have stored in variables. Consider the following code
```javascript
var mood = "happy";
console.log("Today I am feeling " + mood + ".");
```
This statement uses the `+` operator to join our string with the value of the vaiable. In the example above, the console would print "I am feeling happy."

Often we use ES6 string interpolation to make concatination easier. This looks very similar to the satement above, but everything is enclosed between \` and all varaibles are stored between `${}`.

```javascript
var mood = "happy";
console.log(`Today I am feeling ${mood}.`);
```
This would also print "Today I am feeling happy with the value of mood being interpolated in the spot where the variable is in the statement (`${mood}`).

TASKS FOR TODAY
---------------
Today we are going to practice creating, updating, and printing variables. For the coding practice, please do the following:
1. Create 5 variables. These variables should store your (1) First Name, (2) Last Name, (3) age, (4) birth month, and (5) Your favorite number. 
2. Print each of the variables your created in step 1 to the console.
3. It's your birthday! Increase your age by one and print the new value out.
4. Decrease your favorite number by 10 and then multiply it by 2. Print out the new value.
5. Print out the message that tells the user your name, your age, and your birth month.
6. **BONUS**: Using `innerHTML` and `document.querySelector()`, print the value of your first and last name to the `div` with an ID of userOutput. Double triple bonus points if you can also make it enclosed between an h2 tag!.