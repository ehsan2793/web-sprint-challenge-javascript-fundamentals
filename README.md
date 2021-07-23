# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

 .map(): is used to converting data and  need return keyword  and returns a new array the first argument is (item) which refers to  the current element in the array being processed 
 .filter(): requires return statement  and returns a new array automatically  filters results into a new array based on something that can be true or false, if it's true it's included and is moved to the newly formed array if it's false it excluded and does not show in the array.

.reduce():  .reduce gives us back a single value, its usually used for sum or multiply and it takes 2 arguments "accumulator" which is a running total and it takes "item" which is the current value
 initial value is the initial value that the accumulator starts from for example we can give it 10 and it will start from 10 or give it 1, or any other number and it will start from that initial value.

2. Explain the difference between a callback and a higher order function.
 
callback  function are passed into other function as an argument --->  function higherOrder (callback){return ...}
higher order function receive the callback function as arguments

3. Explain what a closure is.

when a function is created within another function, the inside function has an access to the outer function variables  we call that inner function closure
for example :    inner function is the closure because it has access to the "number" that is defined in the outer function does not have access to "value" that is defined in the inner function.
function outer (){
    let number = 10
}return function inner () { 
    let value = 100
    console.log(number, value)
}

4. Describe the four principles of the 'this' keyword.

     *   Window Binding - is viewed as error  and is when none of the rules apply and will give us the global object or undefind in strict mode 

     *  implicit binding - when the function is invoked we look to the left side of the dot and "this" refers to that 

     *  explicit binding -  assign "this" explicitly  using  using .bind , .call , . apply 

     * new bidning - when the function is created  its invoked as constructor function and "this" will point to the new object that is created

5. Why do we need super() in an extended class?

super () tells the child (extended class ) to inherit the attributes and methods of the parent class

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)

