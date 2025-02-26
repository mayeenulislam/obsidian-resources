# Markdown Syntaxes
## 1 Regulars
The syntaxes that can be used in all sorts of Markdown files and will be parsed by any markdown parsers 
***

### 1.1 Headings
Headings are made with Hashes (`#`) and a space afterward
```markdown
# Heading 1
## 2 Heading 2
### 2.1 Heading 3
#### 2.1.1 Heading 4
##### 2.1.1.1 Heading 5
###### 2.1.1.1.1 Heading 6
```
---
### 2.2 Bold/Strong

#### 2.2.1 Using Double Asterisk
```markdown
This is a **Bold** text
```
This is a **Bold** text
#### 2.2.2 Using Double Underscores
```markdown
This is also a __Bold__ text
```
This is also a __Bold__ text

***
### 2.3 Italic/Emphasis

#### 2.3.1 Using Single Asterisk
```markdown
This is an *Italicized* text
```
This is an *Italicized* text

#### 2.3.2 Using Double Underscores
```markdown
This is also an _Italicized_ text
```
This is also an _Italicized_ text

***
### 2.4 Strikethrough
Use 2 Tildes (`~`) to make a text crossed out
```markdown
The text is ~~crossed out~~ within the line
```

The text is ~~crossed out~~ within the line
***
### 2.5 New Line

```markdown
Here is the first line
the next line is separated by just a new line
```

Here is the first line
the next line is separated by just a new line
***
### 2.6 Quotes
```markdown
> Here is a Quote
> <cite>- Said by Him</cite>
```

> Here is a Quote
> <cite>- Said by Him</cite>

***
### 2.7 Lists
#### 2.7.1 Ordered Lists
```markdown
1. Number One
2. Number Two
3. Number Three
```
1. Number One
2. Number Two
3. Number Three

#### 2.7.2 Unordered Lists
##### 2.7.2.1 Using Asterisk (`*`) Sign
```markdown
* List Item First
* List Item Second
* List Item Third
```
* List Item First
* List Item Second
* List Item Third
##### 2.7.2.2 Using Hyphen/Dash/Minus (`-`) Sign
```markdown
- List Item First
- List Item Second
- List Item Third
```
- List Item First
- List Item Second
- List Item Third
##### 2.7.2.3 Using Plus (`+`) Sign
```markdown
+ List Item First
+ List Item Second
+ List Item Third
```
+ List Item First
+ List Item Second
+ List Item Third
***
### 2.8 Checkboxes
```markdown
- [ ] Unchecked Checkbox
- [x] Checked Checkbox
```

- [ ] Unchecked Checkbox
- [x] Checked Checkbox
### 2.9 Horizontal Rule/Separator
Similar to the HTML `<hr/>` tag a separator or horizontal rule will appear using any of the following:
```markdown
***
****
* * *
---
----
- - -
___
____
_ _ _
```

***
### 2.10 Links
#### 2.10.1 Internal Links
##### 2.10.1.1 Link Other File (Raw)
```markdown
[[Link to another File]]
```
[[Link to another File]]
##### 2.10.1.2 Link Other File (Renamed)
```markdown
[[Link to another File|Custom Named]]
```
[[Link to another File|Custom Named]]

#### 2.10.2 External Link
```markdown
[External Link Title](https://example.com)
```
[External Link Title](https://example.com)
#### 2.10.3 Attachment
##### 2.10.3.1 Embed Attachment
```markdown
![](https://picsum.photos/id/24/500/300)
```
![](https://picsum.photos/id/24/500/300)

#### 2.10.4 Table
##### 2.10.4.1 Default Table
```markdown
| Column Header 1 | Column Header 2 | Column Header 3 |
|---|---|---|
| Cell 1, Row 1 | Cell 2, Row 1 | Cell 3, Row 1 |
| Cell 1, Row 2 | Cell 2, Row 2 | Cell 3, Row 2 |
```

| Column Header 1 | Column Header 2 | Column Header 3 |
| --------------- | --------------- | --------------- |
| Cell 1, Row 1   | Cell 2, Row 1   | Cell 3, Row 1   |
| Cell 1, Row 2   | Cell 2, Row 2   | Cell 3, Row 2   |
***
##### 2.10.4.2 Table Cell Alignment
```
| Left Aligned | Center Aligned | Right Aligned |
| :--- | :---: | ---: |
| Cell 1, Row 1   |  Cell 2, Row 1  |   Cell 3, Row 1 |
| Cell 1, Row 2   |  Cell 2, Row 2  |   Cell 3, Row 2 |
```

| Left Aligned | Center Aligned | Right Aligned |
| :--- | :---: | ---: |
| Cell 1, Row 1   |  Cell 2, Row 1  |   Cell 3, Row 1 |
| Cell 1, Row 2   |  Cell 2, Row 2  |   Cell 3, Row 2 |

***
#### 2.10.5 Code
##### 2.10.5.1 Inline Code
Use Backticks (\`) to embrace inline code like this `<br/>` tag
##### 2.10.5.2 Code Block
Use 3 Backticks (\`\`\`) to embrace multiline code block like below:
```
var age = 30;
```
##### 2.10.5.3 Code Block (Indented)
If you indent the line with 4 spaces it will become a code block like below:

    var age = 30;
##### 2.10.5.4 Code Block (Syntax Highlighting)
Use the language after the 3 Backticks (\`\`\`javascript) like below:
```javascript
var age = 30;
```
***
#### 2.10.6 Escape Character
Backslash (`\`) is used to escape Asterisk (`*`), Brackets (`[`), Underscores (`_`) etc. in rare cases
***
### 2.11 LaTeX
LaTeX is a globally recognized syntax for displaying Mathematics and Equations, and is can be used flawlessly in Markdown
***
#### 2.11.1 Math Inline
```latex
$(a+b)^2 = a^2 + 2ab + b^2$
```

$(a+b)^2 = a^2 + 2ab + b^2$

***
#### 2.11.2 Math Block
> [!IMPORTANT] Known Issue
> Newline is not working in Math block as of 2024-04-19

```latex
$$
(a+b)^2 \\
= (a+b) * (a+b) \\
= (a*a + a*b) + (b*a + b*b) \\
= (a^2 + ab) + (ba + b^2) \\
= a^2 + 2ab + b^2
$$
```
$$
(a+b)^2 \\
= (a+b) * (a+b) \\
= (a*a + a*b) + (b*a + b*b) \\
= (a^2 + ab) + (ba + b^2) \\
= a^2 + 2ab + b^2
$$


***

### 2.12 Footnotes

This is a simple footnote[^1].

[^1]: This is the referenced text.
### 2.13 Comment

```
This is an %%inline%% comment.

%%
This is a block comment.

Block comments can span multiple lines.
%%
```
### 2.14 Embed
Any Rich Snippets can be embedded like:
- YouTube
- Twitter etc.
```markdown
![](https://www.youtube.com/watch?v=SwLPto7izu8)
```
![](https://www.youtube.com/watch?v=SwLPto7izu8)
***

## 3 HTML in Markdown
Though some markdown processors work with them, but usually they are not recommended

***
### 3.1 New Line using `<br>` tag
```markdown
Here is the first line<br>
the next line is separated with a Break HTML tag
```

Here is the first line<br>
the next line is separated with a Break HTML tag
***
### 3.2 Center Aligned Text
```html
<center>Center aligned text</center>
```
<center>Center aligned text</center>
***
### 3.3 Right Aligned Text
```html
<p align="right">Right aligned text</p>
```
<p align="right">Right aligned text</p>
