# Stevie's Tutorial

The purpose of this tutorial is to decipher a regex expression and understand what each part of the expression is doing. By doing this we can further understand regex and how it can be used in our every day code. The tutorial will go over each part of a specific regex expression and break down what each function does in the expression.

## Summary

This is the regex expression that I have chosen for this tutorial. This regex expression is used to match emails and to verify somebodies input of an email to make sure that the email is valid. This is a very useful regex expression and it is used almost everywhere, where somebody signs up to link an email to a website this regex expression validates that it is a real email address.

Matching an Email: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components
There are a lot of regex components in this expression, here is a list of all of them. List: ^ , [] , a-z , 0-9 , \. , + , \d , {2,6} , $. Throughout this tutorial these will all be defined and explained on what each component does.
### Anchors
In this regex expression there are 2 different anchors there is the ^ symbol and the $ symbol. The ^ symbol starts the regex expression with the \ symbol. The $ symbol is the end of the regex expression and finishes off the expression. It is usually followed by / for the end of the expression.
### Quantifiers
There is only one quantifier in this expression and that is the + symbol. This symbol means that the things before it must happen at least once or more times. This is necessary for almost all expression because something has to happen in a regex expression for it to be true. The + in this expression means that there needs to be "a-z" and "0-9" at least once or more times and the "_" in that character group signified by the "[]".
### Grouping Constructs
The grouping in this expression is grouping together different text and characters that are entered to the email. ([a-z0-9_\.-]+) This is the first part of the email usually housing the first and last name of a user then maybe some numbers after it then an underscore. After this first grouping of the first part it is inputting an @ symbol then onto the other parts of the expression. ([\da-z\.-]+) This part of the expression is the email part (ex. Gmail or yahoo) of the expression it can be any word a-z. After that part ([a-z\.]{2,6}) it is the tag on the end (ex. .com or .gov), and this section is different because the user can put any character from a-z but the word has to be between 2 and 6 characters long setting up parameters for the tag.
### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
``