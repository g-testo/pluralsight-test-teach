# Polya’s Problem Solving Techniques

## Lesson Objectives:
- Understand Polya’s four steps to problem solving
- Be able to identify and implement these techniques to solve problems

## Prerequisites:

- Variables
- Control Flow
    - If statements
    - Loops
- Functions
    - Parameters, arguments
- Helper methods

## Before we get started:

<details open>
    <summary>What is an algorithm?</summary> <br />

Simple definition: Procedure used for solving a problem.

Format of a programming algorithm: <br />

``` js

// Problem Description: Please create an algorithm that takes in two numbers and returns the sum.

// This is our algorithm:
function sum(input1, input2){
    // This is where you return an output from your algorithm
    return input1 + input2;
}

// This is the invoking of our algorithm:
let output = sum(5, 7);

```
</details>

<details open>
    <summary>Why is learning problem solving techniques important?</summary> <br />
    
- Your mind can go blank when put on the spot to solve a problem. An example would be during an interview. This will give you an instinctual fallback under pressure.

- Some difficult problems can be intimidating and you wouldn't even know where to start. This is a great starting point for any problem.

</details>

<br />

## Polya’s Four Steps:

### Resource: [PDF](https://math.berkeley.edu/~gmelvin/polya.pdf)

<details open>
<summary>First Principle</summary>
    
    Understand the problem

    Can you paraphrase the problem?

    How many input values will the algorithm expect to receive?
    What data type are the inputs?
    What data type and what shape is the output?
    Is there anything you don't understand that you may have to Google?

    What is the good case for solving the problem?
    What kind of edge cases can you think of?
    Are there any other cases that you can think of that you may want to handle?
    Can you write out an example or two of the input(s) and output for each case you came up with?
</details>
<details open>
    <summary>Second Principle</summary>

    Devise a plan

    Are there any helper methods that come to mind when understanding the problem?
    Are you able to pseudocode an algorithm that meets all of the cases you came up with?
    Is there another approach that could solve this problem?

</details>
<details open>
    <summary>Third Principle</summary>

    Carry out the plan

    Where you able to write the code for the pseudocode that you created?
    Do you need to practice/Google how to use a certain helper method?
    Did the plan you devised work?
    Will you have to create a new plan?

</details>
<details open>
    <summary>Fourth Principle</summary>

    Look back

    Is the algorithm scalable with reference to time-complexity/space-complexity 
    How can you refactor the code to make it more time/space efficient?
    Can you refactor the algorithm to be more readable or maintainable?
</details>

## In-class Problem Code-along  [Link](https://www.codewars.com/kata/57eadb7ecd143f4c9c0000a3)

## Student Activity (~ 5 mins):
### Please work on the following problem. Make sure to put extra focus on practicing the four steps and not just solving the problem. [Link](https://www.codewars.com/kata/5715eaedb436cf5606000381)

## More Practice: 
- [Practice Problem 1](https://www.codewars.com/kata/554b4ac871d6813a03000035)
- [Practice Problem 2](https://www.codewars.com/kata/53e30ec0116393fe1a00060b)
- [Practice Problem 3](https://www.codewars.com/kata/558fc85d8fd1938afb000014)