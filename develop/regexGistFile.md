# Regex Tutorial

In this challenge, I'll be explaining the purpose and functionality of a basic "regular expression," or regex. A regex is a sequence of characters that outlines a specific search pattern within code or a search algorithm. These functions are useful when collecting data that needs to meet specific requirements in order to serve the users or for collected data to be functionally represented within an array, for example.  

## Summary

In this challenge, I'll be outlining the regex formula below, which defines the requirements for a valid email address within JavaScript. When these parameters are satisfied, the email address entered can successfully be submitted to an array, algorithm, or function within our given JavaScript code. Please see my breakdown of the formula below.

Matching an Email  – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/


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
- [Literal Characters](#literal characters)
 
## Regex Components

### Anchors
Anchors specify the position of the pattern in relation to a line of text, matching a position before, after, or in between characters.

 / / - The string is contained within these two backslashes 
 ^ - indicates the beginning of the string
 $ - indicates the conclusion of the string



### Quantifiers
Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found.

The + after each [] indicates that any one of the above letters, numbers, or characters can appear an unlimited quantity of times within this part of the email address.
{2,6} - this indicates that, as opposed to the (+) symbol, any of the previously defined characters can appear no less than 2 but no more than 6 times, in whatever order, combination, or repetition.


### OR Operator
OR operators create a logical "either/or" exchange of phrase (four or 4). THERE IS NO "OR" OPERATOR IN THIS REGEX

### Character Classes
Character classes or sets define for the regex acceptable characters for the regex engine. These character classes are enclosed within square brackets [].
Within the [] - 
a-z - indicates that any letters between a-z are acceptable
0-9 - indicates that any numbers between 0-9 are acceptable
_ - indicates that the underscore character ( _ ) is acceptable
\. - the forward slash before the dot (.) isolates the dot, specifying that the ( . ) is acceptable
- - indicates that the dash character ( - ) is acceptable
\d - indicates a digit, indicating that any numbers between 0-9 are acceptable



### Flags
Flags are optional parameters in regex engines that affect the behavior of its search (eg case sensitivity, etc.)
THERE ARE NO FLAGS IN THIS REGEX


### Grouping and Capturing
Grouping and capturing in regex creates groups of subpatterns, allowing for quantifiers for specific sections of the entire formula.

() - the first set of parentheses enclose the first part of the email address (1st capturing group, or everything before the @domain)
() - the second set of parentheses enclose the second part of the email address (2nd capturing group, or the first part of the domain)
() - the third set of parentheses enclose the third part of the email address (3rd capturing group, or the second part of the domain)

### Bracket Expressions
Bracket expressions in regex groups metacharacters within the formula. They help define a character set within a specific part of the search engine.
There are 3 sets of bracket expressions within the formula, listed below. Each one of them exist alone within each of the three capturing groups, defined uniquely with quanitifiers outside of the square brackets but within the parentheses.
[a-z0-9_\.-],[\da-z\.-],[a-z\.]


### Greedy and Lazy Match
Greedy matches will try to match as much input as possible. Lazy matches will try to match the smallest amount of input as possible to satisfy the search.
By default, all the quantifiers of this formula are greedy.

### Boundaries
The anchors ^ and $ serve as the boundaries of this regex, indicating that there are no further characters before of after the email address.

### Back-references
Back references are used to refer to previous capturing groups.
THERE ARE NO BACK REFERENCES IN THIS REGEX.


### Look-ahead and Look-behind
Lookaheads and lookbehinds check for specific patterns in the string without including them in the match (?=... or ?<=...).
THERE ARE NO LOOKAHEADS OR LOOKBEHINDS IN THIS REGEX.

### Literal Characters
The @ symbol appears outside of parentheses or brackets, indicating that it is a necessary part of the formula exactly as it is (once), in its placement.
Similar to the @, the \. following the second capturing group indicates that it is a necessary part of the formula exactly as it is (once), in its placement. The forward slash before the dot ( . ) isolates the dot.

## Author
Cory Feltes - cory.feltes@gmail.com

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
