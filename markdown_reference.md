# markdown reference guide

## text formatting

**bold text** or __bold text__
*italic text* or _italic text_
***bold and italic*** or ___bold and italic___
~~strikethrough text~~
`inline code`

## headings

# heading 1
## heading 2
### heading 3
#### heading 4
##### heading 5
###### heading 6

## lists

### unordered lists
- item one
- item two
  - nested item (2 spaces)
  - another nested item
* alternative bullet
+ another alternative

### ordered lists
1. first item
2. second item
   1. nested numbered item (3 spaces)
   2. another nested item
3. third item

### task lists
- [x] completed task
- [ ] incomplete task

## links

[link text](https://example.com)
[link with title](https://example.com "hover title")
<https://example.com>
[reference link][1]

[1]: https://example.com "reference definition"

## images

![alt text](image-url)
![alt text](image-url "optional title")

## code blocks

```
plain code block
```

```javascript
// syntax highlighted code block
function hello() {
    console.log("hello world");
}
```

## blockquotes

> single line quote
> 
> multiple line quote
> continues here

> nested quote
>> deeper nesting

## horizontal rules

---
***
___

## tables

| column 1 | column 2 | column 3 |
|----------|----------|----------|
| data 1   | data 2   | data 3   |
| data 4   | data 5   | data 6   |

### table alignment

| left aligned | center aligned | right aligned |
|:-------------|:--------------:|--------------:|
| left         | center         | right         |

## line breaks

two spaces at end of line for soft break  
like this

empty line for paragraph break

like this

## escape characters

use backslash to escape markdown syntax:
\*not italic\*
\[not a link\]
\`not code\`

## footnotes

text with footnote[^1]

[^1]: footnote definition

## definition lists

term 1
: definition 1
: definition 1a

term 2
: definition 2

## abbreviations

*[HTML]: hypertext markup language
html is easy to learn

## emphasis alternatives

**strong importance**
*emphasis*
++inserted text++
==highlighted text==

## advanced features

### math (if supported)
$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

### keyboard keys
press <kbd>ctrl</kbd> + <kbd>c</kbd>

### superscript and subscript
x^2^ and h~2~o

### details/summary
<details>
<summary>click to expand</summary>
hidden content here
</details>