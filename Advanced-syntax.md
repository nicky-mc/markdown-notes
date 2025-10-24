Advanced Markdown Syntax
========================

This document explores advanced and extended Markdown syntax and formatting techniques to help you create more sophisticated and structured documents.

Tables with Alignment
---------------------

You can create tables using pipes | and hyphens -. You can control column alignment using colons :.

Left-alignedCenter-alignedRight-alignedContent 1Content 2Content 3Content 4Content 5Content 6Export to SheetsMarkdown

```markdown

   | Left-aligned | Center-aligned | Right-aligned |  |:-------------|:--------------:|--------------:|  | Content 1    | Content 2      | Content 3     |  | Content 4    | Content 5      | Content 6     |   `

Task Lists
----------

You can create interactive task lists (checkboxes) within a list.

*   \[x\] Task 1 (Completed)
    
*   \[ \] Task 2 (Pending)
    
*   \[ \] Task 3 (Pending)
    

Markdown

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   - [x] Task 1 (Completed)  - [ ] Task 2 (Pending)  - [ ] Task 3 (Pending)   `

Code Block Syntax Highlighting
------------------------------

You can add language-specific syntax highlighting to fenced code blocks by specifying the language after the opening backticks.

Python

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   def hello_world():    """Prints 'Hello, world!' to the console."""    print("Hello, world!")  hello_world()   `

Markdown

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   ```python  def hello_world():    """Prints 'Hello, world!' to the console."""    print("Hello, world!")  hello_world()   `

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   ---  ## Extended Text Formatting  Many Markdown flavors support additional text formatting options.  * **Strikethrough:** ~~This text is struck through.~~  * **Highlight:** ==This text is highlighted.== (Note: Not all renderers support this)  * **Subscript (HTML):** H2O  * **Superscript (HTML):** x2  ```markdown  * **Strikethrough:** ~~This text is struck through.~~  * **Highlight:** ==This text is highlighted.==  * **Subscript (HTML):** H2O  * **Superscript (HTML):** x2   `

Footnotes
---------

You can add footnotes to your document, which will be collected at the bottom.

Here is a sentence with a footnote.\[^1\] And here is another.\[^2\]

Markdown

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   Here is a sentence with a footnote.[^1] And here is another.[^note]  [^1]: This is the first footnote text.  [^note]: This is the second, named footnote.   `

Heading IDs and Anchor Links
----------------------------

Most Markdown renderers automatically generate an ID for each heading, allowing you to link directly to it. The ID is typically the heading text in lowercase with spaces replaced by hyphens.

For example, you can link to the Task Lists section.

Definition Lists
----------------

Some extended Markdown processors allow you to create definition lists.

Term 1: Definition 1

Term 2: Definition 2a: Definition 2b

Mathematical Expressions (LaTeX)
--------------------------------

You can include mathematical expressions using dollar signs $ and LaTeX syntax. This is common in scientific and academic contexts (requires a math-enabled renderer like MathJax or KaTeX).

Inline expression: E=mc2

Display expression:

i=1∑n​i=2n(n+1)​

Collapsible Sections (HTML)
---------------------------

You can create collapsible sections (also known as "spoilers" or "accordions") using the

and HTML tags.

Click to expandThis is the hidden collapsible content. You can put any Markdown, including code blocks or images, inside.

Custom Containers (via Blockquotes)
-----------------------------------

While not a formal syntax, a common convention (especially on platforms like GitHub) is to use blockquotes > with bold text to create "alert" or "note" boxes.

> **Note:** This is a custom note container. It helps draw attention to important information.

> **Warning:** This is a custom warning container. Use it for critical warnings or potential issues.

Embedding HTML
--------------

Most Markdown parsers allow you to embed raw HTML for features Markdown doesn't support, like resizing images.

Emoji
-----

You can include emojis in your Markdown documents using their Unicode character or, in many systems, a shortcode.

Shortcode: :smile: :rocket:Unicode: 😄 🚀

This covers some advanced and extended syntax in Markdown. Experiment with these elements to create more dynamic and informative documents!

References
----------

\[^1\]:This is the first footnote text.

\[^2\]:This is the second, named footnote.

---
```markdown
[^1]: This is the first footnote text.
[^note]: This is the second, named footnote.
```
### Tables
```markdown
| Column 1 | Column 2 |
|----------|----------|
| Data 1   | Data 2   |
| Data 3   | Data 4   |
```
### styling
```markdown
**Strikethrough:** ~~This text is struck through.~~
**Highlight:** ==This text is highlighted.== (Note: Not all renderers support this)
**Subscript (HTML):** H2O
**Superscript (HTML):** x2---
###
```markdown
def hello_world():
    """Prints 'Hello, world!' to the console."""
    print("Hello, world!")
hello_world()###
```markdown
```python
def hello_world():
    """Prints 'Hello, world!' to the console."""
    print("Hello, world!")
hello_world()
```
```
### Task Lists
```markdown
* [x] Task 1 (Completed)
* [ ] Task 2 (Pending)
* [ ] Task 3 (Pending)
```
### colour
```markdown
---
## Extended Text Formatting
Many Markdown flavors support additional text formatting options.
* **Strikethrough:** ~~This text is struck through.~~
* **Highlight:** ==This text is highlighted.== (Note: Not all renderers support 
this)
* **Subscript (HTML):** H2O
* **Superscript (HTML):** x2
```
### Code Block Syntax Highlighting
```markdown
```python   
def hello_world():
    """Prints 'Hello, world!' to the console."""
    print("Hello, world!")
hello_world()
```
```
### even more advanced syntax
```markdown
Here is a sentence with a footnote.[^1] And here is another.[^note]
```
### 
```markdown
Click to expand
This is the hidden collapsible content. You can put any Markdown, including code blocks or images, inside.
###
```markdown
> **Note:** This is a custom note container. It helps draw attention to important information.
> **Warning:** This is a custom warning container. Use it for critical warnings or potential issues.
```
###
```markdown
