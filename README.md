# EH-Regex Tutorial

This repo is an introduction to regex (regular expressions).  

## Summary
Regex is a tool used for pattern matching in text, which allows for more efficient data validation, text parsing, and replacing operations within code. 

The main significance of regex is due to that fact that it's versatile, precise, and scalable. It can be used in a variety of platforms and can be used in both small and large data sets. 
This tutorial will explain some things about the key components of regex. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
Anchors are used to indicate the location of a match within a string.  
The most common anchors are ^(start of line) and $(end of line).  

### Quantifiers
Quantifiers specify how many times a character or group of characters should appear in a match.  
Common quantifiers include *(zero or more times), + (one or more times), and ? (zero or one time).  

### OR Operator
OR Operators are used to match any one of a set of characters or patterns.  
The vertical bar (|) is commonly used as an OR operator.  

### Character Classes
Cahracter classes are used to match a specific set of characters.  
For instance , [aeiou] matches any vowel.  

### Flags
A regular expression can be modified using flags.  
Common flags include case-insensitive and global.  

### Grouping and Capturing
These are used to combine elements of a regular expression and take note of a text that matches.  
Using parentheses () allows you to group and capture.  

### Bracket Expressions
These are employed to match any character that occurs within a predetermined set or range. For instance, any lowercase letter matches [a-z].

### Greedy and Lazy Match
These refer to the behavior of quantifiers, and determine whether they should match as much as possible (greedy) or as little as possible (lazy).

### Boundaries
These mark the start or stop of a word or a line.  
Word boundaries (b) and A are examples of typical boundaries (start of string).

### Back-references
These allow the user to use a regular expression to refer to previously captured groups.

### Look-ahead and Look-behind
The terms "look-ahead" and "look-behind" are used to match text that occurs before or after a particular pattern without actually matching the pattern. The symbols for looking forward and looking behind are (?=) and (?=), respectively.

## Author

This tutorial is brought to you by erech. If you wish to learn more, refer to the following GitHub Profile : https://github.com/erech/EH-Regex-Tutorial