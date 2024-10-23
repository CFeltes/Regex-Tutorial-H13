# Regex-Tutorial-H13
Thirteenth homework assignment


# Description
Thirteenth homework assignment - Regex Tutorial


## Summary
In this challenge, I'll be explaining the purpose and functionality of a basic "regular expression," or regex. A regex is a sequence of characters that outlines a specific search pattern within code or a search algorithm. These functions are useful when collecting data that needs to meet specific requirements in order to serve the users or for collected data to be functionally represented within an array, for example. In this challenge, I'll be outlining the regex formula below, which defines the requirements for a valid email address within JavaScript. When these parameters are satisfied, the email address entered can successfully be submitted to an array, algorithm, or function within our given JavaScript code. Please see my breakdown of the formula below.

Matching an Email – /^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/

// - The string is contained within these two backslashes

^ - indicates the beginning of the string () - the first set of parentheses enclose the first part of the email address (1st capturing group, or everything before the @domain) Within the [] - a-z - indicates that any letters between a-z are acceptable 0-9 - indicates that any numbers between 0-9 are acceptable _ - indicates that the underscore character ( _ ) is acceptable . - the forward slash before the dot (.) isolates the date, specifying that the ( . ) is acceptable

indicates that the dash character ( - ) is acceptable The + indicates that any one of the above letters, numbers, or characters can appear an unlimited quantity of times within this part of the email address.
The @ symbol appears outside of parentheses or brackets, indicating that it is a necessary part of the formula exactly as it is (once), in its placement.

() - the second set of parentheses enclose the second part of the email address (2nd capturing group, or the first part of the domain) Within the [] - \d - indicates a digit, indicating that any numbers between 0-9 are acceptable a-z - indicates that any letters between a-z are acceptable . - the forward slash before the dot (.) isolates the dot, specifying that the ( . ) is acceptable Once again, the + indicates that any one of the above letters, numbers, or characters can appear an unlimited quantity of times within this part of the email address.

Similar to the @, the . following the second capturing group indicates that it is a necessary part of the formula exactly as it is (once), in its placement. The forward slash before the dot ( . ) isolates the dot.

() - the third set of parentheses enclose the third part of the email address (3rd capturing group, or the second part of the domain) Within the [] - a-z - indicates that any letters between a-z are acceptable . - the forward slash before the dot (.) isolates the dot, specifying that the ( . ) is acceptable {2,6} - this indicates that, as opposed to the (+) symbol, any of the previously defined characters can appear no less than 2 but no more than 6 times, in whatever order, combination, or repetition.

$ - indicates the conclusion of the string

## Table of Contents
- [User-Story] (#User Story)
- [Acceptance-Criteria] (#Acceptance-Criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)


## User Story
AS A web development student
I WANT a tutorial explaining a specific regex
SO THAT I can understand the search pattern the regex defines

## Acceptance-Criteria
GIVEN a regex tutorial
WHEN I open the tutorial
THEN I see a descriptive title and introductory paragraph explaining the purpose of the tutorial, a summary describing the regex featured in the tutorial, a table of contents linking to different sections that break down each component of the regex and explain what it does, and a section about the author with a link to the author’s GitHub profile
WHEN I click on the links in the table of contents
THEN I am taken to the corresponding sections of the tutorial
WHEN I read through each section of the tutorial
THEN I find a detailed explanation of what a specific component of the regex does
WHEN I reach the end of the tutorial
THEN I find a section about the author and a link to the author’s GitHub profile

## Installation
Step-by-step instructions on how to install and set up your project.

****

## Usage
Instructions on how to use your application.

Visit my sites here!
Gist :
https://gist.github.com/CFeltes/6277622d9605b69c9179e3f78dbee2e0

https://CFeltes.github.io/Regex-Tutorial-H13/
https://github.com/CFeltes/Regex-Tutorial-H13



## Contributing
Guidelines for contributing to the project.
Contributors were the author of the source code, AI, help from the program's tutors, and owner of this repository (Cory Feltes) 

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
Used syllabus/course resources as well as AI resources to check my work.

## Contact Information
Cory Feltes - cory.feltes@gmail.com


//Make sure to keep your README updated as your project evolves!