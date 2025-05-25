# 📘 Markdown Instructional Guide (Raw Syntax)

This guide shows **how to write** Markdown without triggering the formatting. It's perfect for documentation or teaching others.

---

## 📝 Basic Formatting

### Headings

Use `#` for headings. The number of `#` signs determines the heading level:

```
# H1 Heading  
## H2 Heading  
### H3 Heading  
#### H4 Heading  
```

---

### Emphasis

To italicize, bold, or strikethrough text, use the following syntax:

```
*Italic* or _Italic_  
**Bold** or __Bold__
***Bold & Italic*** or ___Bold & Italic___
~~Strikethrough~~
```

Result (when rendered):

*Italic*  
**Bold**  
***Bold & Italic***
~~Strikethrough~~

---

### Lists

#### Unordered List

Use `-`, `*`, or `+`:

```
- Item 1  
- Item 2  
  - Subitem  
```

#### Ordered List

Use numbers followed by a period:

```
1. First item  
2. Second item  
   1. Subitem
```

---

## 🔗 Links & Images

### Links

```
[Link Text](https://example.com)
```

### Images

```
![Alt Text](https://example.com/image.png)
```

---

## 💻 Code

### Inline Code

Use backticks: `` `code here` ``

```
Example: `console.log("Hello");`
```

### Code Block

Use triple backticks (\`\`\`) with optional language:

<pre>
```
```javascript
function greet() {
  console.log("Hello, world!");
}
```
```
</pre>

---

## 📦 Blockquotes

Start a line with `>`:

```
> This is a blockquote.  
> It can span multiple lines.
```

---

## ✅ Checklists

Use `- [ ]` for an unchecked box and `- [x]` for a checked one:

```
- [x] Write guide  
- [ ] Review content  
- [ ] Publish markdown
```

---

## 📊 Tables

Align columns with pipes `|` and dashes `-`:

```
| Name  | Age |  
|-------|-----|  
| Alice |  24 |  
| Bob   |  30 |
```

---

## 🔄 Horizontal Line

Use `---`, `***`, or `___`:

```
---
```

---

## 🧠 Final Tips

- Use backticks (`` ` ``) to show raw Markdown syntax.
- Preview your Markdown in editors like **VS Code**, **Dillinger**, or **Obsidian**.
- Escape special characters by placing a backslash (`\`) before them if needed.
