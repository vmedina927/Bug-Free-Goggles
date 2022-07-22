# Regex (Regular Expressions) Tutorial

The purpose of this tutorial is to provide a better understanding of Regular Expressions (Regex).  Regex is defined as a sequence of characters that defines a specific search pattern.  If included in a code or search algorithms, regular expressions are able to obtain patterns of characters in a string or they can find and replace a character or sequences of characters in a string.

## Summary

The regular expression (Regex) that I will be describing is `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`.  This regular expression is used to match emails and make sure the email follows that correct format.

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

Anchors are what a regular expression starts with and ends with.  In the matching email regex, `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`, the anchors here are the `^` and the `$` character.

### Quantifiers

Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found.  In the matching email regex, `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`, it includes the `+` operator, which connects the users email + email service + `.com`.  Also, another quantifier in this regex is `{2,6}`, in which this will allow a match between the range of 2-6 characters in the character set of `[a-z\.]`.

### OR Operator

There is no OR Operator in this regex, `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/'.

### Character Classes

The character class is `\d` which is pressent in this regex, `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`.  This indicates that it will match a single character, `a-z` after the `@` symbol in an email address.

### Flags

There are no flags present in this regex, `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`.

### Grouping and Capturing

In the regex, `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`, we will define the grouping and capturing.  Grouping and capturing is defined as a way to treat multiple characters as a single unit.  The first capturing group we see is `([a-z0-9_\.-]+)`.  This has to be true in order for us to "match" the following part of the regex.  The second capturing group we see is `([\da-z0-9_\.-]+)`.  Finally, the third and final capturing group we see is `([a-z\.]{2,6})`.

### Bracket Expressions

The bracket expression in this regex, `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`, is one of the capturing groups of `[a-z0-9_\.-]`.  This means that it contains letters between, `a-z` which are case sensitive.  Also, it matches a character between `0-9` as well as the following characters, `_`, `-` and `.`.

### Greedy and Lazy Match

There are no greedy and lazy matches in this regex.

### Boundaries

There are no boundaries in this regex.

### Back-references

There are no back-references in this regex.

### Look-ahead and Look-behind

There are no look-ahead and look-behind in this regex.

## Author

This tutorial was made by Vickiana Medina.

Contact me at vmedina927@gmail.com and find below links to my Github repository and my LinkedIn page.

[Github](https://github.com/vmedina927)

[LinkedIn](https://www.linkedin.com/in/vmedina927/)
