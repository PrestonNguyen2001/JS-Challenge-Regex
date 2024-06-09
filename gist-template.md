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
