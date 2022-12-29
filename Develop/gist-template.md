# Email RegEx Parttern

Matching an Email:` /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

RegEx is a stort tern of "regular expression" and it is a way to watch partern in text. RegEx are often use in search engines, search and repalce funmctions and other programs that manipulated text. For example, yoiu could use a RegEx to search for all tje word in a documt that start with a letter "a" or to find all the phone number in a block of text. Regular expression can be very [owerful, but they can also be compelex and diffucult to read, so it is important to use tham carefully.

## Summary

For the regEx exmail has three partterns. Normally, the email has ` (yourname)@(domain).(extension).(again)`

- `yourname` any letter, numbers, dot and/orhyphens
- `domain` any letter, numbers, dot and/orhyphens
- `extention & again` any letters
- `again` a dot (.) then any letters

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

**Anchors**

The characters `^` and `$` are both considered to be anchors.
Used ` ^` to signify the beginning of the text and `$` marking the end of the tested text.

**Quantifiers**

Quantifiere is the limits of the string that your regex matches (or an individual section of the string). They frequently include the minimum and maximum number of characters that your regex is looking for.

**Grouping Constructs**

The “Matching a Username” regex is fairly straightforward and open-ended about what it accepts. As regular expressions grow more complicated, you may check multiple parts of a string to determine that different sections fulfill different requirements. To break these sections up, you'll need to use grouping constructs.

**Bracket Expressions**

Anything inside a set of square brackets `([])` represents a range of characters that we want to match. These patterns are known as bracket expressions, but they are also known as a positive character group, because they outline the characters we want to include. We can write these expressions to include all of the characters we want to match.

**Character Classes**

Grouping basically just groups up a sequence of regulatory expression tokens into one unit. For example (a-z) is used three times in the code above.

**Flags**

A flag changes the defalt search behavior of a regular expression. For example: "i, g, s, m, y, u" which we do not have in our snippet.

## Author

Tangnay is a fullstack developer, feel free to checkout more samples of her work at https://github.com/Tangnay
