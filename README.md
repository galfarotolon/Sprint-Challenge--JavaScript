# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Description

You will notice there are several JavaScript files being brought into the index.html file. Each of those files contain JavaScript problems you need to solve. If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your team lead

1. Describe the biggest difference between `.forEach` & `.map`.

The .forEach method executes the provided function one time per array element, as it cycles through each element of the array always, and it does not return a new array.

The .map method creates a new array with the results of calling the given function on every element in the array that is being called. It does not manipulate the original array and always needs the “return” keyword in order to work.

2. What is the difference between a function and a method?

A function is a block of reusable code that can be declared or constructed anywhere in the global scope, or nested within other functions.
It passes parameters to operate and can return values.

A method on the other hand is a block of code that is constructed inside an object and can be called using the dot "." notation.

3. What is closure?

Closure is a term that is constantly created once a new function is made. When a new function is created, the scope of anything inside
the function becomes limited by whatever is outside of it. If a variable is declared inside a function, it is unable to be accessed globally, but a variable declared in the global scope can be accessed by the function.

This trend keeps repeating itself when new functions are created within a function, or "nested" inside it. The nested function will be
able to access whatever is outside of it, but not viceversa. The most inner function will always be able to access the rest of data, while
the outer functions are limited and cannot access those functions' variables that are nested within them.

4. Describe the four rules of the 'this' keyword.

1. Window/Global Object Binding - When the keyword "this" is not set or bound within any context or scope (i.e. a function), it will
   automatically refer to the window, which is the whole Javascript language object.

1. Implicit Binding - When you call a function and when the function is invoked, whatever is to the left of the dot
   is what the "this" keyword is going to reference. This is a function invocation.

1. New binding - New binding occurs when creating a Constructor Function. In this case, the keyword "this" refers to the
   specific instance of the object that is created and returned by the constructor function.

1. Explicit binding - When .call or .apply methods are used, this is an example of explicit binding.
   Constructor functions can be modified or altered by using explicit binding.

1. Why do we need super() in an extended class?

Since an extended class is using the same properties/methods than the parent class, super() needs to be used in order to inherit or pass along those properties. When used in a constructor, the super() keyword is used before the rest of the “.this” properties for that specific class are established. It is the glue that connects the parent with the child objects.

## Project Set up

Follow these steps to set up and work on your project:

- [ ] Create a forked copy of this project.
- [ ] Add TL as collaborator on Github.
- [ ] Clone your OWN version of Repo (Not Lambda's by mistake!).
- [ ] Create a new Branch on the clone: git checkout -b `<firstName-lastName>`.
- [ ] Create a pull request before you start working on the project requirements. You will continuously push your updates throughout the project.
- [ ] You are now ready to build this project with your preferred IDE
- [ ] Implement the project on your Branch, committing changes regularly.
- [ ] Push commits: git push origin `<firstName-lastName>`.

Follow these steps for completing your project:

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's Repo).
- [ ] Add your team lead as a Reviewer on the Pull-request
- [ ] TL then will count the HW as done by merging the branch back into master.

## Minimum Viable Product

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

## Task 1: Objects and Arrays

Test your knowledge of objects and arrays.

- [ ] Use the [objects-arrays.js](challenges/objects-arrays.js) link to get started. Read the instructions carefully!

## Task 2: Functions

This challenge takes a look at callbacks and closures as well as scope.

- [ ] Use the [functions.js](challenges/functions.js) link to get started. Read the instructions carefully!

## Task 3: Prototypes

Create constructors, bind methods, and create cuboids in this prototypes challenge.

- [ ] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

## Task 4: Classes

Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.

- [ ] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!
