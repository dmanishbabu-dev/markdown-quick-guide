# _Paragraph_

This is a paragraph

# _Line Break_

2 spaces at the end of line  
newline

Give additional newline for line break

newline

Give additional line breaks with html br tag
<br>
<br>
newline

# _Headings_

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 5

# _Make Text Bold_

**Text is bold**

# _Make Text italic_

_Text is italics_

# _Make Substring Italic_

Substring alic in italic is it*alic*

# _Make Text Bold and Italic_

**_Text is both bold and italics_**

# _Make Text Crossed off_

~~Text is crossed off~~

# _Make Text Highlighted_

Text is ==highlighted== works in some extended versions

Text is <mark>highlighted</mark>

# _Make Text Superscript_

X<sup>2</sup>

# _Make Text Subscript_

H<sub>2</sub>O

# _Render Emojis_

Cheat-Sheet: [Markdown Emojis cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet)

:smile:

:cry:

:laughing:

# _Single line code snippet_

This is code snippet
`print("hello world") #single line code snippet`

# _Multi line code snippet with highlighting, provide language name_

```py
def checkIfPalindrome(s):
    for i in range(len(s)//2):
        if(s[i]!=s[len(s)-i-1]):
            return False
    return True

checkIfPalindrome("madam")
```

# _Hyperlink_

[This is a hyperlink](https://github.com/dmanishbabu-dev)

# _Hyperlink with label same as link_

when you want label and link to be same:

https://github.com/dmanishbabu-dev

or

<https://github.com/dmanishbabu-dev>

# _Render Image_

![Alt text if github logo not rendered due to incorrect path](/github-logo.png)

# _Block Quote_

> This is a block quote

Nested block quotes:

> 1
>
> > 2
> >
> > > 3
> > >
> > > > 4

Here’s a list inside a block quote:

> 1. Item one
> 2. Item two

Here’s a code block:

> ```python
> print("Hello, World!")
> ```

# _Horizontal Line_

`*` or `-` or `_` atleast three times will result in horizontal line

---

---

---

---

---

---

# _Ordered List_

1. First
2. Second
3. Third
4. Fourth
5. Fifth
   1. Nested First
   2. Nested Second

# _Unordered List_

`*` or `-` or `+` can be used for unordered list

- Item 1

* Item 2

- Item 3
  - Nested Item 1
  * Nested Item 2
  - Nested Item 3

# _Unordered List with Nested Ordered List_

`*` or `-` or `+` can be used for unordered list

- Item 1

* Item 2

- Item 3
  1. Nested Item 1
  2. Nested Item 2
  3. Nested Item 3

# _Table_

`:---` Left aligned, default  
`:---:` Center aligned  
`---:` Right aligned

| col1 | col2 | col3 |
| :--- | :--: | ---: |
| A    |  B   |    C |
| D    |  E   |    F |
| H    |  I   |    J |
| L    |  M   |    N |

# _CheckBoX_

- [ ] It's Unchecked

- [x] It's Checked
