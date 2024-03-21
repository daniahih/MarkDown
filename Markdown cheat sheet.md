# Markdown Cheat Sheet

This document provides an overview of various Markdown syntax elements. It's a handy guide for getting familiar with Markdown formatting.

## Headings

Use `#` symbols before your heading text to create headings. More `#` symbols indicate a lower level heading.

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

## Emphasis

You can make text **bold**, *italic*, or ~~strikethrough~~.

```markdown
**bold**
*italic*
~~strikethrough~~
```

## Lists

### Unordered Lists

Use asterisks, plus signs, or hyphens interchangeably.

```markdown
- Item 1
- Item 2
  - Sub Item 2.1
  - Sub Item 2.2
```

### Ordered Lists

Number followed by a dot.

```markdown
1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2
```

## Links

```markdown
[OpenAI](https://www.openai.com)
```

## Images

```markdown
![Alt text](https://www.example.com/image.jpg)
```

## Code

You can use backticks to format code.

### Inline Code

```markdown
`<div>Some inline code</div>`
```

### Code Blocks

Use triple backticks before and after the code block. You can also specify the programming language.

```markdown
```python
def hello_world():
    print("Hello, world!")
```
```

## Blockquotes

```markdown
> This is a blockquote.
```

## Tables

Create tables using dashes for the headers, and pipes for columns.

```markdown
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1    | Data     | Data     |
| Row 2    | Data     | Data     |
| Row 3    | Data     | Data     |
```

## Horizontal Rules

Use three or more asterisks, dashes, or underscores.

```markdown
---
```

## Task Lists

- [x] Completed task
- [ ] Incomplete task
- [ ] Another task to do

