# Understanding Regex

Regular expressions (regex) are powerful tools used in programming for pattern matching within strings. This tutorial will break down a specific regex used to match email addresses and explain each component in detail.


## Summary

Regex, or regular expression is a sequence of characters that forms a search pattern. It is used to match strings that match a specific pattern. Regex is used in many programming languages, including JavaScript, Python, and Ruby. Regex can be used to validate email addresses, phone numbers, and other patterns.

In this tutorial, we will explain the regex pattern used to validate email addresses - `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`.

## Table of Contents

- [Introduction](#introduction)
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

### Introduction

Regular Expressions (regex) are sequences of characters that define a search pattern. They are used to match, locate, or manage text, making it possible to find or replace words within texts. Additionally, regex can be utilized to verify if a text adheres to specified rules.

For example, let's say you have a list of filenames, and you only want to find files with the `.pdf` extension. By using the expression `^\w+\.pdf$`, you can achieve this. The meanings of the components in this expression will become clearer as we go through the steps.

### Anchors

Anchors are used to specify the position in the string where the regex should match.

- `^` asserts the position at the start of the string.
- `$` asserts the position at the end of the string.

In our email regex, the anchors ensure that the entire string must be a valid email address, from start to finish.

### Quantifiers

Quantifiers define the number of times a character or group of characters can occur.

- `*` matches 0 or more occurrences.
- `+` matches 1 or more occurrences.
- `?` matches 0 or 1 occurrence.
- `{n}` matches exactly n occurrences.
- `{n,}` matches n or more occurrences.
- `{n,m}` matches between n and m occurrences.

In our email regex, `+` is used to ensure that there is at least one character in the username and domain name parts.

### OR Operator

The OR operator (`|`) is used to match one pattern or another.
Example: `cat|dog` matches either `cat` or `dog`.

In other contexts, the OR operator can be used to specify alternate acceptable patterns.

### Character Classes

Character classes allow you to match any one of a set of characters.

- `[abc]` matches any one of the characters `a`, `b`, or `c`.
- `[^abc]` matches any character except `a`, `b`, or `c`.
- `[a-z]` matches any lowercase letter.
- `[0-9]` matches any digit.

In our email regex, `[a-z0-9_\.-]` matches any lowercase letter, digit, underscore, period, or hyphen in the username, while `[\da-z\.-]` matches any digit, lowercase letter, period, or hyphen in the domain.

### Flags

Flags modify the behavior of the regex.

- `i` makes the regex case-insensitive.
- `g` makes the regex global, meaning it will find all matches rather than stopping after the first match.
- `m` makes the regex multiline, allowing `^` and `$` to match the start and end of each line.

Although flags are not used in our specific email regex, they can be very useful for other regex patterns.

### Grouping and Capturing



### Bracket Expressions


### Greedy and Lazy Match



### Boundaries


### Back-references




### Look-ahead and Look-behind


## Author
