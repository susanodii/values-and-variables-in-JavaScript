# Values and Variables in JavaScript

![](images/js_logo.jpg)

#### Table of Contents

#### Introduction

#### What are values in JavaScript

#### What are variables in JavaScript

#### How to declare a varables in JavaScript

#### How to store data value to a variable

#### Best practices for naming variables in JavaScript

#### Conclusion

### Introduction

JavaScript is a high level programming langugage that can be used in web development, mobile development, and other other areas of software development.  
In JavaScript, understanding the fundamental concept of values and variables is crucial.When used correctly, they contribute to writing clean, efficient, and maintainable code. 

In this article, you will learn about values and variables in JavaScript with detailed examples and, best practices for naming variables in JavaScript.

### What are values in JavaScript

Values are the smallest unit of information in JavaScript. Every piece of data in JavaScript are considered to contain a value. For example,  
"Susan" is a value. If you want to see this value in the console, type :

```
console.log("Susan")
```

The output is shown below:


![](images/value_img1.png)

From the result above, the output in the terminal is the same with value entered in the console. Values have different data types such as strings, numbers, booleans,arrays, obejects and so on. You can give name to values by assigning them to a variable. Values are reusable when assigned to a variable in order words, when stored in a variable.

### What are variables in JavaScript

Variables are used to store data values and can be accessed throughout the programme.
Variables act like containers that are used to hold values and can be updated and retrieved when needed. For example, in the example used above, the value "Susan" can not be retrieved for use later in the program because it was not stored in a variable.  You can think of a variable as a container that stores the value Susan, each time you want to  use the value Susan, you simply go the container.


### How to declare a variable in JavaScript

You can declare a variable in JavaScript using any of the following reserved keywords:

1. let
2. var
3. const

The example below shows how you can use **var**, **let**, and **const**

```
let myName
var myName
const myName
```


### How to store data value to a variable

You can store data value to a variable using the assignment operator. In JavaScript, the assignment operetor is the "**=**" symbol.To store a value, place your variable on the left side of the symbol and place your value at the right side. Storing a value in a variable at the same time is called
**initializing a variable** The example be shows how to initialize a variable:

```
let myName   = "Susan"
var myName   = "Susan"
const myName = "Susan"
```

Initialized variables can be used over and over again in your codes.

### Best practices for naming variables in JavaScript

When naming variables, use descriptive and easy to understand names. Variable names should easily describe what value it is holding. Descriptive variable names enhances code readability, reusability, and maintability. 

Below are list of best practices for naming varibles in JavaScript:

1. Variable names should always start with either a letter or a dollar sign or an underscore.
   
   ```
   let myName  = "Susan"
   let _myName = "Susan"
   let $myName = "Susan"
   ```

2. Do not begin variable names with numbers, doing so will throw an error. 
   ```
   let 3myName = "Susan"
   ``` 

3. Variable names cannot contain special characters. They can only contain letters, numbers, underscore and dollar sign.
   
   ```
   let first&lastName = "Susan Odii"  // error
   ```
   
4. Do not name variables with reserved keywords in JavaScript. Using reserved keywords will throw an error. 
   ```
   let new = 47 // error
   ```
The code above will throw an error because "new" is a reserved keyword.

5. It is best to name variables in camel case. Camel case means, whenever you have multiple words, you write the first letter of the first word with a small letter, then all the first letters of the subsequent words should begin with a capital letter as shown below:
   ```
   let firstName = "Susan"
   ```
Notice that the first letter of the first word starts with a small letter and the first letter of the next word starts with a capital letter. 

### Conclusion
Values and variables are one of the fundamentals of JavaScript and understanding how to work with them will improve your carrer in programming.

 Values are the smallest units of information in JavaScript and have different data types such as: strings, numbers, booleans, arrays and obejects. 

Variables serves as a containers for holding values and modified and used when the need arises. Variables are initialised when they are assigned a value using the assignment operator. 
 JavaScript has best practices for naming variables and when applied properly, improves your code readability.
