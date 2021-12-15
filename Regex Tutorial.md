# Email Regex

How to write a regex that will validate an email

## Summary

this regular expression is capable of searching for a valid email address
(@)(. +)$
But why, how does it work
well first of the (@) part
this is describing a regular charachter the "@" so its looking for that
followed by (. +)
which translates to a "." followed by more then one character
followed by the $
which is for string replacement

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

(@)(. +)$

### Anchors

$ (dollar) Matches at the end of the string the regex pattern is applied to

### Quantifiers

- (plus) is a quantifier that tells the expression that there is more characters after the dot

### Grouping Constructs

() (parentheses) is a the grouping construct here and it keeps the @ and after the @ seperate

### Bracket Expressions

there are no braket expressions

### Character Classes

the period is a charcther classs and so is the @ they refer to themseves

### The OR Operator

there is no or operator in this regex

### Flags

### Character Escapes

## Author

Kai Gerstley
https://github.com/Kai357
