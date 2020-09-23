# Evaluating Conditions & Conditional statements

There are two components in order for a decision to be implemented:

## Evaluation of a condition

This is where the code checks the current status of the script by comparing 2 values using a comparison, then returns the value to true or false.

## Conditional statements

This is based on the proccess of if/then/else; example:

if (score >) {
    document.write('Message!');
} else {
    document.write('Message2!');
}

### Boolean

Booleans are the results of the evaluation of a situation by comparing one value in the script to what you expect it would be.

Want to know the 4 different boolean results, ![check me out](https://www.lotame.com/wp-content/uploads/2018/11/BooleanLogic-700x350.png)

Booleans are usually an outcome from using if/else statements.
In the JavaScript below;

var pass =50; var score = 75; var msg;
//Pass mark
//Current score
//Message
//Select message to write based on score if (score >= pass) {
msg ='Congratulations, you passed!'; } else {
msg ='Have another go!';
var el = document . getElementByld('answer');
el.textContent =msg;

We can see that an if/else statement allowed us to provide 2 sets of code:

- if the condition value is True,
- if the condition value is False.

A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.

In other words;

switch (level) { case 'One':
IF... ELSE
• There is no need to provide an el se option. (You can just use an if statement.)
vs.
case 'Two':
tit1e = 'Level 2'; break;
case ' Three' :
title = 'Level 3' ; break ;
default :
title= 'Test'; break;
}

The purpose of the switch statement is to present the user with a different message depending on which level they are at. The message is stored in a variable called msg. If a match is found, that code is run; then the break statement stops the rest of the switch statement running.

#### LOOPS

Loops check a condition, so for instance if the return was True, a code block will run, then it will be checked again and again until the condition returns to False.

There are 3 types of loos:

1. FOR LOOP
2. WHILE LOOP
3. DO WHILE LOOP

*The For Loop* is used for when I know the number of times i need to repeat a condition until the return is False.

*The While Loop* is used when we do not know the number of times we will repeat the condition until the answer/return is False.

*The Do While Loop* is very similar to the *while loop*, but will always run the statements inside the curly braces at least once., even if the conidtion returned False.

For more information about the following: 

- [The For Loop](https://cdn.programiz.com/sites/tutorial2program/files/c-for-loop.jpg)

- [The While Loop](https://cdn.journaldev.com/wp-content/uploads/2017/10/while-loop-java.png)

- [The Do While Loop](https://cdn.journaldev.com/wp-content/uploads/2017/10/java-do-while-loop-1.png)

