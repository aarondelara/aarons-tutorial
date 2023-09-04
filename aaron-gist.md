# How to Match an Email with Regex

Welcome to my tutorial of explaining what Regex is.

## Summary

Hey! Do you know what this means? "/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/" If you don't know what any of that means, don't worry, because I will help you understand in this tutorial. These are Rgular Expressions, also known as regex, these are text patterns that are used to search, validate, or even replace text. Today, we will be explaining each component of regex and see how they're used with matching email addresses.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Author](#author)

## Regex Components

### Anchors
The up arrow "^" and dollar sign "$" are both anchors that are used at the beginning of a string and the ending of a string respectively. Since the multiline, "m" is not available, "$" is what signifies the end of a string.
### Quantifiers
The quantifier "+" makes sure that an email address contains the email name, email service, and a domain. For the {2,6} quantifier, it allows a range of 2-6 characters in the character class [a-z\].
### Character Classes
The regex class, "\d"  matches one single digit ranging from 0-9. It can only detect single digit numbers, so not like numbers such as 10 or 100.
### Grouping and Capturing
The purpose of this first capturing of this regex is to match the name of the email ([a-z0-9_\.-]+). The second one matches with the email service ([\da-z\.-]+). Lastly, the third one matches with the domain of the email ([a-z\.]{2,6}).
### Bracket Expressions
The bracket expressions simply matches any letter from a-z and any digit ranging from 0-9. Don't forget that it matches with ".", "_", "-" as well. The expression is [a-z0-9_\.-].
### Greedy and Lazy Match
A greedy quantifier is {} which matches {2,6} for the capture group. It also includes "+" and these will both match as many times as possible.

## Author
Thank you for reading my tutorial! Don't forget that my name is Aaron DeLara and I love to code!! Here is my [GitHub](https://github.com/aarondelara)
