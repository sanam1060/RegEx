# RegEx

Regular Expressions, also known as RegEx or RegExp, are used to extract specific information from text. They are often used to locate or validate a specific string within a larger body of text. Most programming languages support the use of Regular Expressions. This document provides a quick reference to some common RegEx patterns and their uses.

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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
Anchors in RegEx are not used to match any character, but rather to match a specific position in the text. This position may be before or after certain characters. Anchors allow for more precise matching and manipulation of the text.

* The ```^``` anchor in RegEx matches the position at the beginning of the text. This allows the RegEx pattern to only match strings that appear at the start of the text, rather than anywhere within the text.

* The ```$``` anchor in RegEx matches the position at the end of the text. This allows the RegEx pattern to only match strings that appear at the end of the text, rather than anywhere within the text."

Examples:

**```^hello```** - matches any string that **starts with hello**.
![image showing the regular expression caret anchor](./assets/images/regular-expression-caret-anchor.png)

**```said$```** - matches a string that **ends with said**
![image showing the regular expression dollar anchor](./assets/images/regular-expression-dollar-anchor.png)

**```^Fire Department$```** - **exact string match** (starts and ends with Fire Department)
![image showing the regular expression of caret and dollar anchors](./assets/images/regular-expression-caret-and-dollar-anchors.png)

### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
