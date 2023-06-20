# Title (replace with your title)

Introductory paragraph (replace this with your text)

## The Purpose

You are a social media user and you have a phobia of kittens. So, you want to implement something that will find tweets with '#kittens' and block them from view.

Or, you are a password generator, and you do not want to give the same person the same password twice.

In both instances, you need something that can go through arrays of information and find matches or patterns, so that something can be done with them. That is exactly the job for regular expressions.

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

RegEx Anchors are the beginning and end of a search query, much like a capital letter and period marking where the sentence ends and starts.

    This is our example string: "It won’t work on me, I believe in myself"

^I - this will find "I" in the word "It" in our example string, but it will not find "I". When you use this synmbol, a caret, it will search only the very beginning of strings.

    This is our example string: "I will come into my own, yeah yeah"

yeah$ - this will find the last "yeah", but will ignore the first one. The dollar sign is used for finding a pattern only at the very end of a string.

### Quantifiers

Quantifiers are used to specify how many times a character or series of characters can be brought up.

    This is our example string: "The moment you feel, it’s too much"

o - this will give us back 4 seperate o's.
o+ - this will give us back the 'o' from "moment" and "you". It will also give us back the "oo" from "too". The plus sign is saying to find not only 'o', but any string of several o's beside one another.

    This is our example string: "It won’t work on me, I believe in myself"

on? - this will return the 'on' from "won't" and "on". It will also return the single "o" in work. The question mark is saying that the last character is optional, but we want to focus on finding all instances of 'o' still.

    This is our example string: "I will come into my own, yeah yeah"

ow* - this will return the o in "come" and "into". It will also return the "ow" in "own". The star, or asterisk, will look for zero or more of the given letters. It is a combination of the plus sign and the question mark.



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

https://www.youtube.com/watch?v=rhzKDrUiJVk&ab_channel=WebDevSimplified

https://regexr.com/

https://www.rexegg.com/regex-anchors.html

stray kids's blueprint - https://colorcodedlyrics.com/2020/06/17/stray-kids-blueprint-cheongsajin/
