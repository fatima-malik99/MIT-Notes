---
title: "My Markdown Notes"
author: "Fatima Malik"
---
# How to work with .md file
## 1. What is `.md` file?
*A .md file is a Markdown file. It's just a simple text file where you can write content in plain text, but with special characters that make it look nicer or more structured. For example, you can use headings, lists, bold or italic text, and other formatting without needing complex software.*

## 2. How do you use a .md file in Visual Studio Code?
### Create a new ```.md``` file:
1. Open Visual Studio Code.
2. In the __Explorer__ area on the left (where your files are), right-click and select __New File__.
3. Name the file with the ```.md``` extension (like myfile.md).

Once you've done this, you can start typing text in that file. To format that text, you will use Markdown syntax.
### 3. Common Markdown Syntax
Now let's see the common formatting options in Markdown.

#### a) Headers
Headers are titles or headings, and they help organize the content into sections. In Markdown, headers are made using the ```#``` symbol.

```
# This is a big heading (Header 1)
## This is a medium heading (Header 2)
### This is a smaller heading (Header 3)
```
#### b) Bold Text
To make text bold in Markdown, you put two asterisks (**) or two underscores (__) around the word or sentence.
```
**This text is bold.**
__This text is also bold.__
```
#### c) Italic Text
To make text italic (slanted), you put one asterisk (*) or one underscore (_) around the word or sentence.
``` 
*This text is italic.*
_This text is also italic._
```
#### d) Lists
There are two types of lists you can create in Markdown: ordered (numbered) lists and unordered (bulleted) lists.

- **Unordered list:** Use - (dash) or * (asterisk) before each item.
```
- Item 1
- Item 2
```
- **Ordered list:** Use numbers followed by a dot. 
```
1. First item
2. Second item
```
#### e) Links
To add a link (a clickable word that goes to a website), use square brackets [] for the text, and then parentheses () for the URL.
```
[Click here to visit my linkedin profile](https://www.linkedin.com/in/fatima-malik99/)
```
#### f) Images
Images are similar to links, but with an exclamation mark (!) in front of the square brackets.
```
![Alt text for the image](https://www.example.com/image.jpg)
To add an image must place it inside your project folder and provide the correct path
![Alt text for the image](images/my-image.jpg)
```
#### g) Code
If you want to show code or anything that should not be formatted, you use backticks.

-**Inline code:** Put the code inside one backtick (`).
```
`print("Hello, world!")`
```
-**Code block:** For multiple lines of code, use three backticks (```) before and after the code.
```
```print("Hello!")```
```
#### h) Blockquotes
If you want to quote someone or something, you use a greater-than sign (>) at the start of a line.
```
> "The only limit to our realization of tomorrow is our doubts of today."
```
> "If you want to master something, teach it- *Richard Feynman*"
#### i) Horizontal Line
A horizontal line (a line separating content) can be created by typing three hyphens (---).
```
---
```
#### j) Tables
To create a table, you use pipes (|) to separate columns and hyphens (-) to create the table header row.
```
| Name   | Age | Occupation |
|--------|-----|------------|
| Alice  | 30  | Engineer   |
| Bob    | 25  | Designer   |
```
## 4. How to Preview Markdown in Visual Studio Code
Once you've written your Markdown content, you can see how it looks as formatted text:

1. In Visual Studio Code, open the `.md` file.
2. To preview the formatted text, click on the "**Open Preview**" option (it’s an icon at the top right corner of the editor).
3. Or, press the keyboard shortcut `Ctrl+Shift+V` (or `Cmd+Shift+V` on Mac).
This will open a side-by-side view where you can see the raw Markdown on one side and the preview of the formatted text on the other side.