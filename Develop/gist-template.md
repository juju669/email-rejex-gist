# Match an Email Rejex Tutorial
The tutorial will explain the use of rejex to match an expression /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/. Rejex is very useful to validate emails using node inquirer. 

## Summary
Rejex is (short for Regular Expression) a string of text that allows you to create patterns that help match, locate and manage text. The tutorial will explain the rejex of an email. 

## Table of Contents
- [Regex-Components](#rejex-components)
- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)

## Regex Components
This Rejex contains an array of different components such as Anchors, Quantifiers, Character Classes, Grouping and Capturing, Bracket Expressions, Greedy and Lazy Matches, and Boundaries.

### Anchors
The Anchors used for this email rejex, is ^. This is the beginning of the string, or the beginning of a line if the multiline flag (m) is enabled.

### Quantifiers
The Quantiiers used for this email rejex is, + operator, Usually match 1 or more of the proceeding token. Another Quantifier would {2,6}. this allows a match range of 2-6 characters for the character set of [a-z\.].

### Character Classes
The Character class for the email rejex is \d. The rejex matches a single character that is a digit from 0-9. It will only match a single digit. 

### Grouping and Capturing
Capturing group #1 #2,and #3 groups multiple tokens together and creates a capture group for extracting substring or using a backreference
[a-z0-9_\.-]. Capturing group #2 works the same way, [\da-z\.-]. So, Caputre group #3 ([a-z\.]{2,6}).
group1 matches the user email name. group2 matches the email service, group3 captures the .com

### Bracket Expressions
Bracket Expressions for this email rejex includes sets of a-z0-9_\.-], this matches any letter a-z which is case sensitive. This will also match 0-9 and match the proceeding characters "_" , "-" , [\da-z\.-].

### Greedy and Lazy Match
This also includes greedy match.
+,{},'{2,6}

### Boundaries
The boundries are represented by \b and\B.


## Author
My name is Julian Wilson, I'm an aspired web developer always looking to learn in the world of coding. Please checkout my github profile. https://github.com/juju669





