# INTRO-CS-4 - Algorithm Design and Problem Solving - Advanced

## Arrays

#### Exercise #1 
Open up a blank repl.it set to Javascript. Copy the code below into your workspace:

```
var arr = ["This", "is", "a", "sentence."];
function printOutString() {
  // your code here
}

printOutString();
```
Complete the function to print out the string `This is a sentence.`

#### Exercise #2
Write a function that:
* Takes in an array of numbers
* Doubles the value of each number in the array
* Prints out the new updated array

Example: 
Given an array `[1, 2, 4, 5]`. 
The output should be `[2, 4, 8, 10]`

#### Exercise #3
Write a program to compute the sum and product (multiplication) of an array of numbers. Print out the sum and the product.

Example:
Given an array `[1, 2, 3, 4]`
The sum is 10.
The product is 24.

#### Exercise #4
Write a program that takes in an array of numbers and returns the largest number in the list.
Example:
The given array is  `[3, 5, 7, 1, 6]`
The largest number is 7.

#### Exercise #5
```
var student1Courses = ['Math', 'English', 'Programming'];
var student2Courses = ['Geography', 'Spanish', 'Programming'];
```
Create a program that loops over the 2 arrays and if there are any common courses print them out to the console.


#### Exercise #6
For each of the exercises below, assume you are starting with the following people array.

`var people = ["Maria", "Dani", "Luis", "Juan", "Camila"];`

1. Write a command that prints out all of the people in the list.
2. Write the command to remove "Dani" from the array.
3. Write the command to remove "Juan" from the array.
4. Write the command to add "Luis" to the front of the array.
5. Write the command to add your name to the end of the array.
6. Using a loop, iterate through this array and after console.log-ing "Maria", exit from the loop.
7. Write the command that gives the indexOf where "Maria" is located.

At the end of the exercise, there should be 4 people in the array.

## Sorting

#### Exercise #1
Write a program to sort a list of numbers in descending order (from highest to lowest).

#### Exercise #2
Write a program to sort a list of names alphabetically.

#### Exercise #3
Write a program to ...

## Code Refactoring & Fixing Code

#### Exercise #1
1. Code and paste the code below into a repl.it (set to Javascript).
2. Make sure to run the program the understand the output.
3. Find ways to improve the code and make it clearer to understand.

```
function someFunction(list) {
  if (list.length === 0) {
    return 0;
  }
  
  return list.length;
}
```

#### Exercise #2
1. Code and paste the code below into a repl.it (set to Javascript).
2. Make sure to run the program the understand the output.
3. Find ways to improve the code and make it clearer to understand.

```

```

#### Exercise #3
*Step 1*
Write a program that takes in two lists and returns the greatest number out of the two lists. 
Hint: call the function from Array Exercise #4 (make sure that Array Exercise #4 returns a single number - the greatest number in the list).

*Step 2*
1. Find a partner. 
2. Exchange your code. 
3. Read your partner's code and suggest improvements on how you would refactor their code.
4. Test your partner's code for correctness (does it give the correct output), if it does not give the correct output, work together to fix the code.

## Additional Exercises

#### Arrays
```
var values1= ['Apple', 1, false];
var values2 = ['Fries', 2 ,true];
var values3 = ['Mars', 9, 'Apple'];
```
Create a function that compares the 3 arrays and find any common elements. Print out the common elements.
