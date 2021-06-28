# Regular Expression - Matching a Hex value

The purpose of this gist is to explore the Regular Expression responsible for matching Hex values.

## Summary

A Regular Expression, often times referred to as a Regex, is a sequence of characters that specifies a certain search pattern; usually used as string-searching algorithm's that find strings that match the conditions set in the Regex. This gist is going to delve into the Regex that matches Hex values, the Regex is as follows  `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`. 

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

The anchors in this Regex are `^` and `$`. 

`^` indicates that the string must begin with the character that immediately follows it. In our Regex, the expression starts with `/^#`, in this, we see that a `#` follows the `^`, and as such, states that the string must start with a `#` to be a match. 

`$` indicates that the string must match the preceeding pattern. In the matching Hex values Regex, `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`, this means that the string must match the `{6}` or `{3}` that finishes of the expression. Note: the `|` signifies 'or', hence why the `$` applies to the `{6}` OR the `{3}`, this will be discussed in a bit.

### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
