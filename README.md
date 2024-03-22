# [JSL03] Project Submission: Which one is which? Declarative or Imperative?!

Loom Recording Link: https://www.loom.com/share/e288599b30904df489524248eb35a959?sid=407759c9-25bd-4d76-be8a-d2c21c08a2ae

# Project Overview

In this project, I was presented with two JavaScript code examples, each demonstrating a different programming paradigm: imperative and declarative. My task was to analyse these examples and determine which one follows an imperative programming style and which one follows a declarative programming style. 

I presented my reasoning for each example, recorded my presentation using Loom, and submit my findings along with the Loom recording to the Project Tab on the Learning Management System (LMS).

# Presentation Talking Points

# Example #: 1

## Imperative Approach 
Example one JavaScript code is written using imperative programming, as it has a function which contains steps of what to do, having a direct control over the execution of each statements. The type of imperative programming used in this code is procedural programming as it demonstrates sequential execution, local variable scope and modularity. 

The code contains a function called “cookSteak” which takes two parameters, the steakWeight and the desiredDoneness. Inside the function two variables are made which have 0 values. 

The grillTemperature variable has the number 204 assigned to it for the first step which indicated state modification, for the second step a constant variable named seasoning is created which has the string salt and pepper assigned to it. For the third step a while loop is created which will run while the steakTemperature is less than the temperature of the desiredDoneness, while now hardcoded in the comments it says that the steaktemperature variable will be updated along with the grilltemperature, both demonstrating explicit state manipulation. All of these are characteristics of imperative programming . For step four we have an conditional statement which checks if the steak temperature is >= the desiredDoness which if true will return the string the steak is ready to serve. Then has an else statement which will return the string steak needs more cooking. The loop and conditional statements are control structures of imperative programming. 

The function is assigned to a constant variable named results , the function is assigned along with its two arguments for the steakweight and desired doneness. The result variable is then passed to the console.log. Due to the while loop condition and the fact that the variable steakTemperature is not getting updated in the code , this while loop will keep running forever. But the overall code should console.log either Steak is ready to serve or Steak needs more cooking. 


# Example #: 2

## Declarative Approach 
The second Example JavaScript code is written using declarative programming. The aim of this code is to give a process of cooking a steak which is console.log’d when calling the function with its arguments. The reason why it is a declarative program is because of the fact that this code tells the computer what to do instead of how  due to the fact that the code is not broken down to multiple steps firstly and secondly the code utilizes an array which has the steps which are placed inside objects which contains the key as action and the value as the step of the process to be executed, the objects also contain parameters which either contain key/value or parameter or variable as a property. 

The code also doesn’t explicitly write out the step for the process, instead a loop is utilized which iterates over the steps using the predefined array. Inside the loop a switch statement is used to determine which action is to be taken for each step based on the value provided in the switch statements. While having access to the cooking Process array we then console.log cooking steps inside string literals and accessing the values or properties from the array objects. 

Thus, when the cook Steak function is called with its arguments, the code runs which prints out all the steps which is what we wanted the code to do and shows values passed as arguments. 

Both the arrays with objects along with the loop which contain the switch statements makes the code more readable and less error prone. 

# Learning Outcome 
What I learned from analyzing these two codes, is that although some code might easily end up as imperative programming, you could still tweak code in a way which makes it do what you want instead of how to do things. I managed to learn to see through the finer details to differentiate between the two codes because also the fact that the example one code looked like it had less code when compared to example two, I had to remember that the logic which will handle the temperature changing for steakTemperature and grill temperature was not yet added to the while loop in the first code. I also learned more about declarative programming since I had to do a lot more research to confirm that the second example was declarative programming. 

