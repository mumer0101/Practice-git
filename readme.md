# Practicing Git and GitHub  
## Learning Markdown  

---

### How Headlines Work:
You can use `#` symbols for headings — the more `#`, the smaller the heading.

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

---

### Text Formatting:

**Bold Text:**
```markdown
**bold**
__bold__
```

*Italic Text:*
```markdown
*italic*
_italic_
```

~~Strike Through Text:~~
```markdown
~~strike through~~
```

> **Blockquote / Quotation:**
```markdown
> Quotation
```

---

### Lists in Markdown:

**Unordered Lists:**
```markdown
- Hyphens
* Asterisks
+ Plus sign
```

**Ordered Lists:**
```markdown
1. First ordered list item
   * Unordered sub-list.
1. Numbers don't really matter
```
(*Note: Markdown will auto-correct the numbering even if you write all as `1.`*)

---

### Writing Code Blocks:

For inline code:  
\`code here\` → `code here`

For multiline code block:
<pre>
```
this is for writing a code
```
</pre>

---

### Adding Images:

**Simple Image Syntax:**
```markdown
![Github Logo](https://images.seeklogo.com/logo-png/30/2/github-logo-png_seeklogo-304612.png)
```

**Reference-style Image Link:**
```markdown
![Github Logo]

[Github Logo]: https://images.seeklogo.com/logo-png/30/2/github-logo-png_seeklogo-304612.png
```

**Image Inside a Clickable Link:**
```markdown
[![Github Logo](https://images.seeklogo.com/logo-png/30/2/github-logo-png_seeklogo-304612.png)](https://www.linkedin.com/in/muhammad-umer-8b12b1272/)
```

---

### Creating Tables:

```markdown
| Left   | Center   | Right   |
|--------|:--------:|--------:|
| One    | Two      | $1.00   |
| Three  | Four     | $120.00 |
| Five   | Six      | $.99    |
```

- `:---:` → center alignment  
- `---:` → right alignment  
- `---` → left alignment  

---

### Collapsible Section (Details Tag):

```html
<details>
<summary>collapsed</summary>

# Header

This is the copy for the collapsed text.
</details>
```

Useful when you want to **hide long content** and show it when clicked.
