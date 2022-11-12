![Ultimate Markdown Logo](UM-Logo1.jpg)

# __Ultimate-Markdown__

The ultimate Markdown cheatsheet! A comprehensive, (eventually) all-encompassing Markdown reference.

Much of the beginning information can be found at the links given below, however this Readme provides a concise and well-formatted reference sheet all in one place.

<br>

## Why?

It started when I needed a good reference for Markdown, as I was still a beginner trying to learn how to make good and professional-looking documentation on Github, Jupyter, and for code in general. I searched through Github, it wasn't a complete search, but of several I found, it never seemed complete or as well-formatted as I thought it could be. I decided to make something more, an entire community on Github for Markdown, and a strong, yet still concise, to-the-point reference at the core of it all.

<br>

## References

Refer to https://www.markdownguide.org/basic-syntax/ and https://www.markdownguide.org/extended-syntax/ for the complete standard reference.

<br>

[![ForTheBadge built-by-developers](https://forthebadge.com/images/badges/built-by-developers.svg)](https://GitHub.com/SpyrossS3/)

[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](https://commonmark.org)
[![GitHub license](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://github.com/SpyrossS3/Ultimate-Markdown/blob/main/LICENSE)
[![HitCount](https://hits.dwyl.com/SpyrossS3/Ultimate-Markdown.svg?style=flat-square&show=unique)](https://hits.dwyl.com/SpyrossS3/Ultimate-Markdown)

<br>

# Table of Contents

- [Headers](#headers)
  - [Header 1](#header-1)
  - [Header 2](#header-2)
  - [Header 3](#header-3)
  - [Header 4](#header-4)
  - [Header 5](#header-5)
  - [Header 6](#header-6)
  - [Header Level 1](#header-level-1)
  - [Header Level 2](#header-level-2)
- [Paragraphs](#paragraphs)
- [Line Breaks](#line-breaks)
- [Emphasis](#emphasis)
  - [Bold](#bold)
  - [Italic](#italic)
  - [Bold and Italic](#bold-and-italic)
- [Blockquotes](#blockquotes)
  - [Blockquotes with Multiple Paragraphs](#blockquotes-with-multiple-paragraphs)
  - [Nested Blockquotes](#nested-blockquotes)
- [Lists](#lists)
  - [Ordered Lists](#ordered-lists)
  - [Unordered Lists](#unordered-lists)
- [Code](#code)
  - [Code Blocks](#code-blocks)
  - [Fenced Code Blocks](#fenced-code-blocks)
    - [Syntax Highlighting](#syntax-highlighting)
- [Horizontal Rules](#horizontal-rules)
- [Links](#links)
  - [Adding Titles](#adding-titles)
  - [URLs and Email Addresses](#urls-and-email-addresses)
  - [Reference-style Links](#reference-style-links)
- [Images](#images)
  - [Image Linking](#image-linking)
- [Escaping Characters](#escaping-characters)
- [Tables](#tables)
  - [Alignment](#alignment)
    - [Left Alignment](#left-alignment)
    - [Center Alignment](#center-alignment)
    - [Right Alignment](#right-alignment)

<br>

# Headers

> Always remember to include a space after # and to leave == and -- on the line directly below your header.

<br>

# Header 1

    Markdown: # Header 1

<br>

## Header 2

    Markdown: ## Header 2

<br>

### Header 3

    Markdown: ### Header 3

<br>

#### Header 4

    Markdown: #### Header 4

<br>

##### Header 5

    Markdown: ##### Header 5

<br>

###### Header 6

    Markdown: ###### Header 6

<br>

Header Level 1
====

    Markdown: Header Level 1
            ====  

<br>

Header Level 2
----

    Markdown: Header Level 2
            ----

<br>

# Paragraphs

> Paragraphs are only separated by a blank line break inbetween paragraphs and any additional formatting preference is left to the author.

<br>

Paragraph example 1.

Paragraph example 2.

    Markdown: Paragraph example 1.

            Paragraph example 2.

<br>

# Line Breaks

> In Markdown, to leave a line break, you would put two spaces after text and press enter to continue on the next line, but as this is hard to see in an editor, the HTML tag: `<br>` is a much better choice in terms of clean raw formatting.

<br>

Example 1.  
Example 2.
<br>
Example 3.

    Markdown: Example 1.  
              Example 2.
              <br>
              Example 3.

<br>

# Emphasis

## Bold

---

<br>

> You can use either ** or __ for a bold effect, but since you can only use ** for text within text, I would advise focusing strictly on ** usage.

<br>

**Example 1.**

__Example 2.__

Ex**ampl**e 3.

    Markdown: **Example 1.**

            __Example 2.__

            Ex**ampl**e 3.

<br>

## Italic

---

<br>

> You can use either * or _ for a italic effect, but since you can only use * for text within text, I would advise focusing strictly on * usage.

<br>

*Example 1.*

_Example 2._

Ex*ampl*e 3.

    Markdown: *Example 1.*

            _Example 2._

            Ex*ampl*e 3.

<br>

## Bold and Italic

---

<br>

> You can use either \*\*\*, ___, or \_\_\*, \*\*\_ for a italic effect, but since you can only use \*** for text within text, I would advise focusing strictly on \*** usage.

<br>

***Example 1.***

___Example 2.___

__*Example 3.*__

**_Example 4._**

    Markdown: ***Example 1.***

            ___Example 2.___

            __*Example 3.*__

            **_Example 4._**

<br>

# Blockquotes

> Example 1.

    Markdown: > Example 1.

<br>

## Blockquotes with Multiple Paragraphs

---

<br>

> Example 1.
>
> Example 2.

    Markdown: > Example 1.
            >
            > Example 2.

<br>

## Nested Blockquotes

---

<br>

> Example 1.
>
>> Example 2.

    Markdown: > Example 1.
            >
            >> Example 2.

<br>

# Lists

## Ordered Lists

---

<br>

1. Example 1.
2. Example 2.
   1. Example 3.
   2. Example 4.
3. Example 5.
        
        Markdown: 1. Example 1.
                2. Example 2.
                  1. Example 3.
                  2. Example 4.
                3. Example 5.

<br>

## Unordered Lists

---

<br>

- Example 1.
- Example 2.
  - Example 3.

<br>

* Example 1.
* Example 2.
  * Example 3.

<br>

+ Example 1.
+ Example 2.
  + Example 3.

        Markdown: - Example 1.
                - Example 2.
                  - Example 3.

                <br>

                * Example 1.
                * Example 2.
                  * Example 3.

                <br>

                + Example 1.
                + Example 2.
                  + Example 3.

<br>

# Code

`This is a code example.`

    Markdown: `This is a code example.`

<br>

## Code Blocks

---

<br>

> Code blocks are created by indenting each line by four spaces or one tab (two tabs in VS Code).
> 
> (It may be more convenient to use fenced code blocks, explained ahead.)

<br>

    This is a code block.

<br>

## Fenced Code Blocks

---

<br>

````
<h2>
  Hello! This is an example!
</h2>
````

    Markdown: ````
              <h2>
                Hello! This is an example!
              </h2>
              ````

<br>

### Syntax Highlighting

````python
text = "Hello"

for x in text:
  print(x + x)
````

    Markdown: ````python
              text = "Hello"

              for x in text:
                print(x + x)
              ````

# Horizontal Rules

<br>

***

---

___

    Markdown: ***

            ---

            ___

<br>

# Links

> There is a compatibility issue with spaces in links. For best outcome, use %20 in a link where there should be a space.

<br>

Click here to go to [Google](https://google.com).

    Markdown: Click here to go to [Google](https://google.com).

<br>

## Adding Titles

---

<br>

Click here to go to [Google](https://google.com "Google Oogle").

    Markdown: Click here to go to [Google](https://google.com "Google Oogle").

<br>

## URLs and Email Addresses

---

<br>

<https://amazon.com>

<example@gmail.com>

    Markdown: <https://amazon.com>

            <example@gmail.com>

<br>

## Reference-style Links

---

<br>

> You can position the referenced link(s) anywhere else further down in the document.

<br>

[example][1]

[1]: https://google.com/images (example)

    Markdown: [example][1]

            [1]: https://google.com/images (example)

<br>

# Images

![Mona is hulaing... ^^](https://octodex.github.com/images/hula_loop_octodex03.gif)

    Markdown: ![Mona is hulaing... ^^](https://octodex.github.com/images/hula_loop_octodex03.gif)

<br>

## Image Linking

---

<br>

[![Noir Mona](https://octodex.github.com/images/privateinvestocat.jpg)](https://en.wikipedia.org/wiki/Film_noir)

    Markdown: [![Noir Mona](https://octodex.github.com/images/privateinvestocat.jpg)](https://en.wikipedia.org/wiki/Film_noir)

<br>

# Escaping Characters

\* This would be an asterisk without the backslash.

    Markdown: \* This would be an asterisk without the backslash.

<br>

> The following listed can be escaped by a \ where they would otherwise be used to format text in Markdown.

<br>

    Escapable Characters:
    
        Backslash: \
        
        Backtick: `

        Asterisk: *

        Underscore: _

        Curly Braces: { }

        Brackets: [ ]

        Angle Brackets: < >

        Parentheses: ( )

        Pound Sign: #

        Plus Sign: +

        Minus Sign (hyphen): -

        Dot: .

        Exclamation Mark: !

        Pipe: |

<br>

# Tables

> Although you can have varying cell widths, it doesn't look as readable as one that does have matching widths. You may want to create tables with some other tool or extension.
> 
> A couple to try: 
> 
> https://www.tablesgenerator.com/markdown_tables
> https://anywaydata.com/

| Column 1  | Column 2  |
| --------- | --------- |
| Headers   | Titles    |
| Palala    | Text      |

    Markdown: | Column 1  | Column 2  |
              | --------- | --------- |
              | Headers   | Titles    |
              | Palala    | Text      |

<br>

## Alignment

---

<br>

### Left Alignment

| Column 1  | Column 2  |
| :-------- | :-------- |
| Headers   | Titles    |
| Palala    | Text      |

    Markdown: | Column 1  | Column 2  |
              | :-------- | :-------- |
              | Headers   | Titles    |
              | Palala    | Text      |

<br>

### Center Alignment

| Column 1  | Column 2  |
| :-------: | :-------: |
| Headers   | Titles    |
| Palala    | Text      |

    Markdown: | Column 1  | Column 2  |
              | :-------: | :-------: |
              | Headers   | Titles    |
              | Palala    | Text      |

<br>

### Right Alignment

| Column 1  | Column 2  |
| --------: | --------: |
| Headers   | Titles    |
| Palala    | Text      |

    Markdown: | Column 1  | Column 2  |
              | --------: | --------: |
              | Headers   | Titles    |
              | Palala    | Text      |

<br>

