#Advanced Sytntax
This document explores advanced Markdown syntax and formatting techniques to help you create more sophisticated documents.
##Task Lists
You can create task lists using hyphens `-` or asterisks `*
- [ ] Task 1
- [x] Task 2
- [ ] Task 3
* [ ] Task 1
* [x] Task 2
* [ ] Task 3
```markdown
- [ ] Task 1
- [x] Task 2
- [ ] Task 3
* [ ] Task 1
* [x] Task 2
* [ ] Task 3
```
##Tables    
You can create more complex tables with alignment options using colons `:`. 
```markdown
| Left-aligned | Center-aligned | Right-aligned |
|--------------|----------------|---------------|
| Content 1    | Content 2      | Content 3     |
| Content 4    | Content 5      | Content 6     |
|:-------------|:--------------:|--------------:|
| Left-aligned | Center-aligned | Right-aligned |
| Content 1    | Content 2      | Content 3     |
| Content 4    | Content 5      | Content 6     |
``` markdown
| Left-aligned | Center-aligned | Right-aligned |
|--------------|----------------|---------------|
| Content 1    | Content 2      | Content 3     |
| Content 4    | Content 5      | Content
    6     |
|:-------------|:--------------:|--------------:|
| Left-aligned | Center-aligned | Right-
| Content 1    | Content 2      | Content 3     |
| Content 4    | Content 5      | Content 6     |
```
##Footnotes
You can add footnotes to your document using square brackets `[]` and a caret `^
Here is a sentence with a footnote.[^1]

[^1]: This is the footnote text.
```markdown
Here is a sentence with a footnote.[^1]

[^1]: This is the footnote text.
```
##Definition Lists
You can create definition lists using terms followed by a colon `:` and their definitions.
```markdown
Term 1:
Definition 1

Term 2:
Definition 2
Term 3:
Definition 3
```markdown
Term 1:
Definition 1

Term 2:
Definition 2
Term 3:
Definition 3
```
##Mathematical Expressions
You can include mathematical expressions using dollar signs `$` and LaTeX syntax.
Inline expression: $E=mc^2$
Display expression: $$E=mc^2$$
```markdown
Inline expression: $E=mc^2$
Display expression: $$E=mc^2$$ 
```
##Collapsible Sections
You can create collapsible sections using the `<details>` and `<summary>` HTML tags.
<details>
<summary>Click to expand</summary>
This is the collapsible content.
</details>
```markdown
<details>
<summary>Click to expand</summary>
This is the collapsible content.
</details>
```
##Custom Containers
You can create custom containers using blockquotes `>` and special markers.
> **Note:** This is a custom note container.
> **Warning:** This is a custom warning container.
> **Error:** This is a custom error container
```markdown
> **Note:** This is a custom note container.
> **Warning:** This is a custom warning container.
> **Error:** This is a custom error container
```
##Emoji
You can include emojis in your Markdown documents using their shortcode or Unicode.
Shortcode: :smile:
Unicode: Shortcode: :smile:
Unicode: 😄
Shortcode: :smile:
Unicode: 
    😄😄😄
```markdown
Shortcode: :smile:
Unicode: 😄
Shortcode: :smile:
Unicode: 
    😄😄😄
```
##Tables
You can create tables using pipes `|` and hyphens `-` to separate columns and headers.      
```markdown
| Column 1 | Column 2 |
|----------|----------|
| Data 1   | Data 2   |
| Data 3   | Data 4   |
```markdown
| Column 1 | Column 2 |
|----------|----------|
| Data 1   | Data 2   |
| Data 3   | Data 4   |
```
This covers some advanced syntax and formatting techniques in Markdown. Experiment with these elements to create more dynamic and informative documents!

##
##References
- [Markdown Guide - Extended Syntax](https://www.markdownguide.org/extended-syntax/)
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [CommonMark Spec](https://commonmark.org/spec/)
##
##