Regex Tutorial: Matching an Email 

A Regular Expression (or Regex) is a filter that is used to fing certain sequences of characters in text. 

## Summary

The purpose of this tutorial is to look at the different components that make up regular expressions and how they can be used to to verify user emails.
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- 
## Regex Components

### Anchors
Anchors are characters that have no other purpose than to "anchor the regex", they don't represent a character. The caret ^ indicates the beginning of the regex while the dollar sign $ indicates the end of the expression. All regexes are also started and ended with a /.

/^           ([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})               $/
   
### Quantifiers
Quantifiers specifies how many times a character may appear, most quantifiers are outlined in curly brackets {}. In our regex, our quantifiers as {2 AND 6}. 
### Character Classes
Character classes are used to define between different kinds of characters, like letters, digits, or other special characters. 
### Grouping and Capturing
Grouping and capturing are executied by using the () symbols. if you look at our regex /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ we have 3 groupings. 
### Bracket Expressions
Bracket Expressions are parameters within the []that your regex can match. For example, the first bracket,[a-z0-9_\.-] tells us that the string CAN contain lowercase letters a thru z, contain numbers 0 thru 9, and include the proceeding special characters. 


## Author
You can see more of my repositories at https://github.com/jschneringer

