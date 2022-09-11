# RegEx Tutorial and Explanation

With this code, I'll go over an example of regular expression that was given to us.

## Summary

The Reg Ex that I will be summarizing would be the email Reg Ex that was given to us.
 /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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

### Anchors
The ^ and $ are used as anchors in the expression. In the example, they are used to start and end the expression following a forward slash and prior to the ending forward slash. The ^ is used to mark the beginning of the expression and the $ is used to mark the end.
### Quantifiers
THe Quantifiers, or *+?{}, are used to add a limit, to match the string following a certain code. In our example, it is written out as ([###])+ with the plus being the quantifier. It means it is followed up with one more object.
### Grouping Constructs
() - grouping and capturing - the parentheses create a group and holds the value of what is inside it. They will need to match the value before the grouping with the values that are grouped in the parentheses. You are able to also create 

### Bracket Expressions
[] - the bracket expression is used to match the string with the value and order as inside the bracket. In our example, they use a filter in the bracket expression. In the expression, they contain a string that represents a hexadecimal digit and numerical value alongside special characters.
### Character Classes
The Character classes, or \d \w\s and . are used to determine the datatype of the value. It can be used to match wheter a character is a digit, word, space, or any character at all.
### The OR Operator
[] - or operator - find the match of code before the [] and the match within the values of the []. 
### Flags
There are a few different types of flags when it comes to regex. It'll follow the ending of the two slashes and whether it will repeat, start,end or even make the whole expression case sensitive. The regex will be followed with a g (global), m(multi-line), or an i (insensitive). 
### Character Escapes
Character escapes are special characters that are used to represent different instances in the reg ex. For example, \w+ is used to represent a characters name. They are represented in numerous ways but are different enough to be considered special characters that represent another value such as spaces, names, decimals, and more.


## Author
