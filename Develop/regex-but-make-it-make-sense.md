# Regular Expresssion....but 💫 make it make sense 💫

Are you a baddie and you don't know what Regular Expressions are? You've come to the right place girly-pop. We have an example regex for you to reference AND a tutorial on how the hell to read it hehe.... Put on your bugglegum pink lip gloss and high heels and slay this journey with me, baby girl!

## Summary

In this tutorial, we will go over what a regular expression consists of. 
A regular expression is a way to search through a string of text. Kinda like a map at the entrance to the mall! In this tutorial, we will be using the following regex as a reference:\

Matching a Hex Value: `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/` \
Let's call her Sally!

Sally is designed to match hexadecimal colors to use on your cutest CSS stylesheet or HTML page.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)

## Regex Components

Regular Expressions are comprised of different components that come together to create a search pattern. Some common components include anchors, quantifiers, character classes, flags, and boundaries. Think of components like accessories! Earrings, shoes, bracelets, rings, bags, etc... All of these come together to complete your outfit! (And you can mix and match hehe <3)

### Anchors

Anchors are generally used to match the beginning, end, and in-between character positions in a string. In Sally's scenario, the ^ is used in the beginning of the string, and $ is used at the end. This means that the entire pattern must match from the start to the end of the string. Sally's hat color matches her shoes and her fit also goes kinda crazy bc it's all matching!

### Quantifiers

Quantifiers is a tool that counts or describes how many times a character or group of characters are allowed to appear in the text. In Sally's case, there are no explicitly used quantifiers. There is, however, what we can call a a greedy quantifier and the "{6}" and "{3}" are greedy quantifiers by default. {6} means we want exactly 6 characters while matching as many characters as possible in order for the expression to continue to be valid. Sally basically can only go to six stores in the morning, and three more in the afternoon (I think any baddie would hate this ugh!! Only 9 stores all day sounds so boring smh) 

### OR Operator

OR operators is represented by "|" symbol. It's just a logical way of saying either the left OR right of the symbol is allowed to match. Options, baby! You wanna wear the heart earrings, or the hoops? The choice is flexible!

For Sally, `[a-f0-9]{6}` can have EITHER 6 characters that consists of characters between the lowercase letters a-f and/or numbers between 0-9 OR "|" `[a-f0-9]{3}` can have 3 characters of the same features. 

### Character Classes

Character Classes are used to define specific sets of characters that can be used in a search pattern! So like we went over in OR Operator above, the character class "a-f" means that within the boundaries of each of the greedy quantifier, the hexidecimal can only consist of lowercase characters between a-f. The same concept goes along with "0-9"! This is Sally's outfit concept. Does she want to dress cottage core or goth mommy? Are we into E-girl, or Soft-girl? The concept is CRUCIAL just like character classes are crucial in regular expressions!

### Grouping and Capturing

Regular expressions can also be captured in parts or in all of a match into a group. The "()" are used to capture a group. For example, 

`([a-f0-9]{6}|[a-f0-9]{3})`

is capturing two groups with an OR operator separating each alternative. Do you like mixing your lipsticks with your eyeshadow? I didn't think so!! Baddies are organized babygirls!

### Bracket Expressions

Bracket expressions define character classes. It specifies a set of characters that regular expressions can match to any single character. Sally's character class "a-f0-9" is within these brackets! 

## Author

My name is Hye-Ji. I love long walks on the beach, a growth mindset, and coding! You can also say I'm a girl's girl hehe 


