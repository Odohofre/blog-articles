---
title: "Markdown Essentials: A Beginner's Guide"
seoTitle: "Markdown essentials for learners, professionals, writers, programmers."
seoDescription: "Learn Markdown from scratch with this beginner's guide. Master basic syntax, formatting, and more. Start creating stylish web content today!"
datePublished: Thu Sep 21 2023 19:35:39 GMT+0000 (Coordinated Universal Time)
cuid: clmtkp37h000909ma7shnf0ts
slug: markdown-essentials-a-beginners-guide
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/zIwAchjDirM/upload/bacd7616ad03cb5c7217a0bb17a9b682.jpeg
tags: writing, markdown, documentation

---

In today's digital age, the need for proficient content creation is greater than ever. Markdown, a game-changer for web content, offers simplicity and accessibility. Markdown is here to simplify web document creation for developers, bloggers and writers.

## Prerequisites

This article assumes that you're a total beginner, and no previous knowledge is assumed.

## Introduction

Markdown lies at the heart of web content creation. It is a lightweight markup language, that's simple and readable, even for non-coders. What makes Markdown stand out are its simplicity, versatility, and wide applications.

Imagine formatting text without complex HTML tags or bulky word processors. Markdown offers you a solution that combines both. You get to style content, add links, embed images, and organize writing with a few symbols.

For instance, to italicize a phrase you add a single asterisk (`*`) before and after it (eg. `*italic*` ). Or create a heading using a `#` symbol in front of the text. (eg. `# Heading one`).

### Markdown's Popularity

Many people love Markdown. Programmers like it for its simple syntax that helps them focus on content. Bloggers enjoy its text styling, and technical writers find it great for clear docs.

But Markdown isn't only for pros. You can use it on social media, forums, and content systems. It's easy to read and user-friendly. Learning Markdown gives you valuable skills and connects you to a worldwide community dedicated to clear communication.

### What this Article covers

In this article, we'll demystify Markdown, starting with the basics and gradually exploring advanced concepts. By the end, you'll have a solid grasp of Markdown's core syntax. This expertise empowers you to create clear and stylish web content and documents with ease.

Whether you're new and curious or an experienced writer, join me as we explore Markdown together. Unlocking its power to craft clear and stylish web content.

## Basic Syntax

You will often use these basic elements for content formatting in Markdown.

You can test your codes using [Dillinger](https://dillinger.io/).

### Headings

Headings are used to structure your documents.

To make a heading, start the phrase or word with a hash sign `#`. The heading level should match the number of "`#`". The greater the number of "`#`" symbols, the lower the heading level.

#### Example 1

```Markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

Output:

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

### Lists

In Markdown, lists can either be ordered or unordered.

For an **unordered** list, you can use either "`*`", "`+`", or "`-`" to show the list item.

#### Example 2.1

```Markdown
* Item 1
* Item 2
* Item 3
```

Output:

* Item 1
    
* Item 2
    
* Item 3
    

In an **ordered** list, use numbers followed by periods (**.**) to indicate the list item.

#### Example 2.2

```Markdown
1. First item
2. Second item
3. Third item
```

Output:

1. First item
    
2. Second item
    
3. Third item
    

### Links

To create links, use square brackets `[]` for the link text and parentheses `()` for the URL.

#### Example 3

```Markdown
[Open Google](https://www.google.com)
```

Output:

[Open Google](https://www.google.com)

Clicking the link opens the Google homepage.

### Images

To add images, use an exclamation mark (`!)`, followed by square brackets (`[])` for alt text, and finally, parentheses "`()`" for the image URL (i.e. `![alt text](image URL)`). You can optionally use quotation marks `""` to add a title after the URL.

#### Example 4

```Markdown
![Meditation by the sea](meditation.jpg)
![Meditation by the sea](meditation.jpg "meditating by the ocean")
```

Output:

![Markdown image example - Meditation by the sea](https://cdn.hashnode.com/res/hashnode/image/upload/v1694519937460/a32bc362-15cf-4bcd-9103-2754c6bb54c5.jpeg align="left")

### Emphasis

To emphasize text, surround it with double asterisks `**` or double underscores `__` to make it **bold**. Also, surround the text with a single asterisk `*` or single underscore "\_" on both sides to italicize it.

#### Example 5

```markdown
**Bold Text**
*Italic Text*
```

Output:

**Bold Text**

*Italic Text*

### Code

Use backticks (`` ` ``) to enclose a word, or phrase and signify it as code.

#### Example 6

```Markdown
To install a package, use the `npm install` command
```

Output:

To install a package, use the `npm install` command

### Horizontal Rules

To make a horizontal rule, simply place three or more asterisks (`***`), dashes (`---`), or underscores (`___`) on a separate line.

#### Example 7

```Markdown
Horizontal rule
***
```

Output:

Horizontal rule

---

### Combining basic elements

You can combine basic Markdown syntax to format content more effectively.

1. Heading with emphasis: Merge a second-level heading with bold text or add emphasis. For Example:
    
    ```Markdown
    ## **Important Notice**
    ```
    
    Output
    
    > ## **Important Notice**
    
2. Unordered list with links: Blend an unordered list with hyperlinks. You can use it to create a table of contents. Example:
    
    ```Markdown
    - [Github](https://www.github.com)
    - [Twitter](https://www.twitter.com)
    ```
    
    Output
    
    * [Github](https://www.github.com)
        
    * [Twitter](https://www.twitter.com)
        
3. Link in a heading: Combine a hyperlink and a heading.
    
    ```Markdown
    ## [My Twitter](https://www.twitter.com/B_Odohofre) page
    ```
    
    Output
    
    > ## [My Twitter](https://www.twitter.com/B_Odohofre) page
    
4. List of links with emphasis: Combine an unordered list with both bold and italic text. For example:
    
    ```Markdown
    - **[GitHub](https://www.github.com)**
    - *[Google](https://www.google.com)*
    ```
    
    Output:
    
    * [**GitHub**](https://www.github.com)
        
    * [*Google*](https://www.google.com)
        
5. Mixed emphasis In a list: This demonstrates how you can mix emphasis styles within a list. For example:
    
    ```plaintext
    - _Italic_
    - **Bold**
    - _Italic and **Bold**_
    ```
    
    Output:
    
    * *Italic*
        
    * **Bold**
        
    * *Italic and* ***Bold***
        

## Other Elements

Not all Markdown apps support this extended syntax. First, check if your app supports the syntax you need. If not, you need to use a different Markdown processor.

### HTML

According to the creator of Markdown [Jack Gruber](https://daringfireball.net/projects/markdown/syntax#html)

> Markdown is not a replacement for HTML, or even close to it.
> 
> For any markup not covered by Markdown's syntax, you simply use HTML itself.
> 
> The only restrictions are that block-level HTML elements - e.g. `<div>`, `<table>`, `<pre>`, `p`, etc. - must be separated from surrounding content by blank lines, and the start and end tags of the block should not be indented with tabs or spaces.
> 
> Inline elements - `<span>`, `<cite>`, or `<del>` - can be used anywhere.

### Tables

To include tables, three or more hyphens (`---`) to create each column's header. Use pipes (`|`) to separate each column. For compatibility, you should also add a pipe on either end of the row.

#### Example 8

```Markdown
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
```

Output:

| Syntax | Description |
| --- | --- |
| Header | Title |
| Paragraph | Text |

### Strikethrough

To strike through words, use two tilde symbols (`~~`) before and after the words.

#### Example 9

```Markdown
~~The world is flat.~~ We now know that the world is round.
```

Output:

<s>The world is flat.</s> We now know that the world is round.

### Escaping Characters

To display a literal character that would otherwise be used to format text in a Markdown document, add a backlash (`\`) in front of the character.

#### Example 10

```Markdown
\* Without the backlash, this would be a bullet in an unordered list.
```

Output:

\* Without the backlash, this would be a bullet in an unordered list.

## Conclusions

In this guide, we've covered most of the things you need to know about Markdown. From the basics to advanced techniques, you've learnt how to

* Structure content with headings
    
* Create lists,
    
* Add links and images,
    
* Emphasize text and many more.
    

Now, it's your turn to apply what you've learnt. Dive deeper into Markdown, experiment with different combinations, and enhance your content creation skills. Whether you're a beginner or an experienced writer, Markdown empowers you to communicate with clarity and style in the digital realm.

As you embark on your Markdown journey, don't forget to explore the extra resources provided for continuous learning and improvement. Happy Writing!

## Further Resources

* [Markdown Tutorial](https://www.markdowntutorial.com/). An open-source website that teaches Markdown through interactive exercises.
    
* [Awesome Markdown](https://github.com/mundimark/awesome-markdown). A list of Markdown tools and learning resources.
    
* [README checklist](https://github.com/ddbeck/readme-checklist). Helps you write better README for your project.
    

## Attribution

* [John Gruber's Markdown documentation](https://daringfireball.net/projects/markdown/). The creator of Markdown original guide.
    
* [Markdown Guide](https://www.markdownguide.org/). A free and open-source reference guide that explains how to use Markdown.