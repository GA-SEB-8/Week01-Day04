<h1>
  <span class="headline">Intro to JavaScript Functions Lab</span>
  <span class="subhead">Exercise</span>
</h1>

## Introduction

This lab provides an opportunity to practice defining and calling functions in JavaScript.

### A quick note before you dive in

If you find yourself stuck during the lab, we encourage you to revisit the lesson materials first. They're designed to provide you with the information and examples that will help you complete the exercises.

If you've revisited the materials and are still facing challenges, don't hesitate to collaborate with your classmates.

Lastly, the internet is filled with resources specific to JavaScript functions. Websites like [Google](https://www.google.com/), [MDN Web Docs on Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions), and [Stack Overflow](https://stackoverflow.com/questions/tagged/javascript+functions) are just a few clicks away. Use these as a last resort before reaching out for help.

Happy coding!

## Lab Exercises

Copy and paste each of the following exercises into your JavaScript file. To check your work, open the `index.html` file in a web browser and inspect the browser console.

### Exercise 1: `maxOfTwoNumbers()`

```js
/*
Exercise 1: maxOfTwoNumbers()

In this exercise, create a function named maxOfTwoNumbers. 
It should take two numbers as inputs and return the larger number. 
If they're equal, return either one.

Exercise 1 has been completed for you:
*/

function maxOfTwoNumbers(x, y) {
  if (x >= y) {
    return x;
  } else {
    return y;
  }
}

console.log('Exercise 1 Result:', maxOfTwoNumbers(3, 9));
```

### Exercise 2: `isAdult()`

```js
/*
Exercise 2: isAdult()

Write a function named isAdult. It should take an age (number) 
and return 'Adult' if the age is 18 or over and 'Minor' otherwise.

Example: isAdult(21) should return 'Adult'.

Complete the exercise in the space below:
*/



console.log('Exercise 2 Result:', isAdult(21));
```

### Exercise 3: `isCharAVowel()`

```js
/*
Exercise 3: isCharAVowel()

Write a function named isCharAVowel that takes a single character as 
an argument. It should return true if the character is a vowel and 
false otherwise. For the purposes of this exercise, the character 
y should not be considered a vowel.

Example: isCharAVowel('a') should return true.

Complete the exercise in the space below:
*/



console.log('Exercise 3 Result:', isCharAVowel("a"));
```

### Exercise 4: `generateEmail()`

```js
/*
Exercise 4: generateEmail()

Create a function named generateEmail. It should take two strings: 
a name and a domain. It should return a simple email address.

Example: generateEmail('johnsmith', 'example.com') 
should return 'johnsmith@example.com'.

Complete the exercise in the space below:
*/



console.log('Exercise 4 Result:', generateEmail("johnsmith", "example.com"));
```

### Exercise 5: `greetUser()`

```js
/*
Exercise 5: greetUser()

Define a function called greetUser. It should take a name and a 
time of day (morning, afternoon, evening) and return a personalized 
greeting.

Example: greetUser('Sam', 'morning') should return "Good morning, Sam!"

Complete the exercise in the space below:
*/



console.log('Exercise 5 Result:', greetUser("Sam", "morning"));
```

### Exercise 6: `maxOfThree()`

```js
/*
Exercise 6: maxOfThree()

Define a function, maxOfThree. It should accept three numbers 
and return the largest among them.

Example: maxOfThree(17, 4, 9) should return 17.

Complete the exercise in the space below:
*/



console.log('Exercise 6 Result:', maxOfThree(5, 10, 8));
```

### Exercise 7: `calculateTip()`

```js
/*
Exercise 7: calculateTip()

Create a function called calculateTip. It should take two arguments: 
the bill amount and the tip percentage (as a whole number). 
The function should return the amount of the tip.

Example: calculateTip(50, 20) should return 10.

Complete the exercise in the space below:
*/



console.log('Exercise 7 Result:', calculateTip(50, 20));
```

### Exercise 8: `convertTemperature()`

```js
/*
Exercise 8: convertTemperature()

Write a function named convertTemperature. 
It takes two arguments: a temperature and a string representing the 
scale ('C' for Celsius, 'F' for Fahrenheit). 
Convert the temperature to the other scale.

Example: convertTemperature(32, 'C') should return 89.6 (Fahrenheit).
Example: convertTemperature(32, 'F') should return 0 (Celsius).

Complete the exercise in the space below:
*/



console.log('Exercise 8 Result:', convertTemperature(32, "C"));
```

🎉  You did it!  🎉
