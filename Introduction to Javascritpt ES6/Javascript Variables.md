# JavaScript Variables and the `prompt()` Function

## Introduction
In this lesson, we explore how to store and retrieve user input using variables in JavaScript.

## Using `prompt()` for User Input
```javascript
var myName = prompt("What is your name?");
```
- The `prompt()` function displays a dialog box asking the user for input.
- The user's input is stored in the variable `myName`.

## Storing Data in Variables
```javascript
var myName = "Angela";
```
- `var` is a keyword used to declare a variable.
- `myName` is the variable name.
- `"Angela"` is the assigned value (a string).

## Retrieving Stored Data
```javascript
console.log(myName); // Outputs: Angela
```
- The stored value can be accessed using `console.log()`.

## Updating Variables
```javascript
myName = "Jack Bauer";
console.log(myName); // Outputs: Jack Bauer
```
- Variables declared with `var` can have their values updated.
- The `var` keyword is not required when updating an existing variable.

## Combining Strings and Variables
```javascript
alert("My name is " + myName + ", welcome to my course!");
```
- The `+` operator concatenates strings and variable values.

## Using Variables in a Game Example
```javascript
var gameLevel = 1;
gameLevel = 2;
gameLevel = 3;
alert("Your level is currently: " + gameLevel);
```
- Variables can store numerical values and be updated dynamically.
- `alert()` displays the current game level.

## Summary
- **`prompt()`** allows user input.
- **Variables store data** for later use.
- **Strings and numbers** can be stored and updated dynamically.
- **Concatenation (`+`)** allows dynamic message creation.

This foundational knowledge is crucial for building interactive web applications!
