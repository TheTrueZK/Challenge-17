# Regex Tutorial

AS A web development student
I WANT a tutorial explaining a specific regex
SO THAT I can understand the search pattern the regex defines

## Summary

A Regex, or regular expression, is a sequence of characters that define a search's parameters.
We will look at an example denoting a proper email address.

Example: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

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

* `^` matches the start of the string.
* `$` matches the end of the string.

### Quantifiers

* `+` Matches 1 or more of the preceding token.
* `*` Matches 0 or more of the preceding token.
* `?` Matches 0 or 1 of the preceding token, effectively making it optional.

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

* `?` Makes the preceding quantifier lazy, causing it to match as few characters as possible. 
By default, quantifiers are greedy, and will match as many characters as possible.

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
