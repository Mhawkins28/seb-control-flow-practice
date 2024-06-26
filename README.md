# Functions and Control Flow Practice

The purpose of this exercise is to practice working with control flow. Think of it
as doing reps or practicing scales! The more you practice, the better you'll
get.

## Prerequisites

- Fundamental JavaScript: syntax, data types
- Conditions: including `if`, `if`/`else`, and `if`/`else if`/`else`
- Loops: `for` loops

## Setup and Instructions (tentative)

1. Do the work in the [challenge.js](challenge.js) file.
2. In the javaScript file, complete the excercies and `console.log` each exercise's answer.
3. Be sure to number each function with a comment above it.

## Exercises

#### Prompt 1

1. Create a variable called age and assign it to your age (or any number). Write a conditional that matches the following conditions:
   - if age is less than or equal 19, print "You're still a teenager!"

#### Prompt 2

2. Expanding on the previous exercise, write a conditional that matches the following conditions:
   - if the age is less than 0 or greater than 120, print "Invalid age"
   - if the age is between 0 and 12 (inclusive), print "A Child!"
   - if the age is between 13 and 19 (inclusive), print "Teenager"
   - if the age is 60 or above, print "Senior"

#### Prompt 3

3. Create a variable called `someNumber` and assign it a random number between 0 and 100.

- Create a conditional that matches these requirments:
  - if someNumber is less than 30, print "that's a small number"
  - if someNumber is between 30 and 60, print "the number is medium sized"
  - if someNumber is greater than 60, print "We got a big one!"

#### Prompt 4

4. Write a `for` loop that iterates over the numbers 1 to 20 and prints whether or not a number is even or odd.
   - Example console log: "[number] is even" or "[number] is odd"

### Level UP

#### Prompt 5

5. Using your favorite emoji, draw a square using a `for` loop. You may build a 10x10 square to start, but you also may draw any rectangle.
   > Hint: You will need to use a nested loop for this exercise.

## Solution

Try not to peek!

<details>
<summary> 🔎 Possible Solutions</summary>

```js

// PROMPT 1

let age = 17;  // You can assign any number to age

if (age <= 19) {
  console.log("You're still a teenager!");
}


// PROMPT 2

let age = 18; // You can assign any number to age
if (age < 0 || age > 120) {
    console.log("Invalid age");
} else if (age >= 0 && age <= 12) {
    console.log("A Child!");
} else if (age >= 13 && age <= 19) {
    console.log("Youths");
} else if (age >= 20 && age <= 59) {
    console.log("Adult");
} else if (age >= 60) {
    console.log("Time to retire!");
}

// PROMPT 3

const someNumber = 50;
// or you can use const someNumber = Math.floor(Math.random() * 101);

if (someNumber < 30) {
  console.log("That's a small number.");
} else if (someNumber >= 30 && someNumber <= 60) {
  console.log("The number is medium sized.");
} else {
  console.log("We got a big one!");
}


// PROMPT 4

for (let num = 1; num <= 50; num++) {
    if (num % 2 === 0) {
        console.log(`${num} is even`);
    } else {
        console.log(`${num} is odd`);
  }
}


// PROMPT 5 - LEVEL UP.

for (let i = 0; i < 10; i++) {
  let row = '';
  for (let j = 0; j < 10; j++) {
    row += '🚀';
  }
  console.log(row);
}

//output:
🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀
🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀
🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀
🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀
🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀
🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀
🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀
🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀
🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀
🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀
```

</details>
