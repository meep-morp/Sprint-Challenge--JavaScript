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

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your team lead

- [ x ] Briefly compare and contrast .forEach & .map (2-3 sentences max)

    .forEach loops through each index of an array and returns what the anonymous function does. Does not make a new array .map goes through the specified array or key and changes it and inserts the results into a new array.

- [ x ] Explain the difference between a callback and a higher order function.

    A higher order function is a function that takes other functions as parameters. A callback is the argument that goes into a higher order function. 

- [ x ] What is closure?

    Accessing functions from a parent-level-scope, in child-level-scope, even after that function has been terminated/returned.

- [ x ] Describe the four rules of the 'this' keyword.

    1. Window Binding: Where 'this' defaults to. Refers to the global window object in the console. 
    2. Implicit Binding: The most common, 'this' refers to what is to the left of the '.'. 'This' is implied.
    3. Explicit Binding: Defing 'this' with one of the three built-in methods: .Call, .Apply, .Bind. .Call and .Apply immidiently runs a function from the passed in object and .bind makes a new function that can be saved for later.
    4. New Binding: 'this' refers to the new object constructed from the parent class.

- [ x ] Why do we need super() in an extended class? Super binds props and prototypes to the new class. Replaces .create in the new syntax. 

## Project Set up

Follow these steps to set up and work on your project:

- [ x ] Create a forked copy of this project.
- [ x ] Add TL as collaborator on Github.
- [ x ] Clone your OWN version of Repo (Not Lambda's by mistake!).
- [ x ] Create a new Branch on the clone: git checkout -b `<firstName-lastName>`.
- [ x ] Create a pull request before you start working on the project requirements.  You will continuously push your updates throughout the project.
- [ x ] You are now ready to build this project with your preferred IDE
- [ x ] Implement the project on your Branch, committing changes regularly.
- [ x ] Push commits: git push origin `<firstName-lastName>`.

Follow these steps for completing your project:

- [ x ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo).
- [ x ] Add your team lead as a Reviewer on the Pull-request
- [ x ] TL then will count the HW as done by  merging the branch back into master.


## Minimum Viable Product

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

## Task A: Objects and Arrays
Test your knowledge of objects and arrays. 
* [ x ] Use the [objects-arrays.js](challenges/objects-arrays.js) link to get started.  Read the instructions carefully!

## Task B: Closure
This challenge takes a look at closures as well as scope.

* [ x ] Use the closure.js link to get started. Read the instructions carefully!

## Task C: Prototypes
Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [ x ] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

## Task D: Classes
Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* [ x ] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

- [ x ] There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!
