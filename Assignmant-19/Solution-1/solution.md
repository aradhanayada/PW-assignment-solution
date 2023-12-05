# Solution
## Conditional Statements in JavaScript

Conditional statements in JavaScript allow you to control the flow of your program based on certain conditions. They help you execute different blocks of code depending on whether a specified condition evaluates to true or false.

### Syntax:

```javascript
if (condition) {
    // Code to be executed if the condition is true
} else if (anotherCondition) {
    // Code to be executed if anotherCondition is true
} else {
    // Code to be executed if none of the above conditions are true
}
Examples:
Basic If Statement:

let age = 18;

if (age >= 18) {
    console.log("You are eligible to vote.");
}
If-Else Statement:

let temperature = 25;

if (temperature > 30) {
    console.log("It's a hot day.");
} else {
    console.log("It's not too hot today.");
}
If-Else If-Else Statement:

let number = 0;

if (number > 0) {
    console.log("Number is positive.");
} else if (number < 0) {
    console.log("Number is negative.");
} else {
    console.log("Number is zero.");
}

These examples illustrate the basic structure of conditional statements in JavaScript. Depending on the evaluation of conditions, different blocks of code will be executed. Modify the conditions and code inside each block to meet the specific requirements of your JavaScript program.
