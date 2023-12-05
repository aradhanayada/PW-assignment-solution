# Solution
## Loops in JavaScript

Loops in JavaScript are used to repeatedly execute a block of code until a certain condition is met. They are essential for performing repetitive tasks efficiently.

### 1. **`for` Loop:**

The `for` loop is used when the number of iterations is known in advance.

#### Syntax:
  
     for (initialization; condition; update) {
     // Code to be executed in each iteration
     }
 **Example:**
 
    for (let i = 0; i < 5; i++) {
    console.log("Iteration", i);
    }
### 1. **`while` Loop:**

The while loop is used when the number of iterations is not known in advance, and the loop continues as long as a specified condition is true.

**Syntax:**

     while (condition) {
    // Code to be executed as long as the condition is true
     }
**Example:**

    let count = 0;

    while (count < 3) {
      console.log("Count:", count);
      count++;
     }
### 1. **`do-wile` Loop:**
Similar to the while loop, but it ensures that the code inside the loop is executed at least once before checking the condition.

**Syntax:**
   
     do {
       // Code to be executed
      } while (condition);

**Example:**

     let x = 0;
  
      do {
        console.log("Value of x:", x);
        x++;
    } while (x < 3);
### 1. **`for...in` Loop:**
Iterates over the enumerable properties of an object.

**Syntax:**

      for (variable in object) {
        // Code to be executed for each property
      }

**Example:**
    
     const person = { name: "John", age: 30, occupation: "Developer" };

      for (let key in person) {
        console.log(`${key}: ${person[key]}`);
      }
### 1. **`for...of` Loop:** 
Introduced in ECMAScript 6, iterates over the values of an iterable object (e.g., arrays, strings).

**Syntax:**
 
     for (variable of iterable) {
       // Code to be executed for each value
      }
**Example:**

      const colors = ["red", "green", "blue"];

     for (let color of colors) {
       console.log(color);
     }
These loops provide different ways to iterate over data structures or execute code repeatedly based on specific conditions. Choose the appropriate loop based on the requirements of your program.
