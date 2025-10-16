# Markdown Cheat Sheet

Use these examples to remember common Markdown patterns. Copy/paste to try them.

---

## Headings

# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternate H1 and H2 styles:

Heading 1
=========

Heading 2
---------

---

## Emphasis

Italic: *text* or _text_

Bold: **text** or __text__

Bold + Italic: ***text*** or ___text___

Strikethrough (GFM): ~~text~~

---

## Paragraphs and Line Breaks

This is a paragraph. End a line with two spaces  
to force a line break.

Or use an explicit HTML break:<br>Line after a break.

---

## Lists

Unordered lists (any of -, +, * works):

- Item A
- Item B
  - Nested B1
  - Nested B2
    - Nested B2a

Ordered lists (numbers can repeat; order is rendered):

1. First
1. Second
1. Third
   1. Nested 3.1
   1. Nested 3.2

Task lists (GFM):

- [x] Done item
- [ ] Pending item
  - [ ] Nested task

---

## Links

Inline link: [OpenAI](https://openai.com)

Title attribute: [OpenAI](https://openai.com "OpenAI Homepage")

Autolink (GFM): <https://openai.com>

Reference-style:

[OpenAI][openai]

[openai]: https://openai.com

---

## Images

Inline image:

![Alt text describing the image](https://via.placeholder.com/200x100 "Optional title")

Image wrapped in a link:

[![Alt text](https://via.placeholder.com/120x60)](https://example.com)

Reference-style image:

![Logo][logo]

[logo]: https://via.placeholder.com/80x80

---

## Code

Inline code: `console.log("hello")`

Fenced code blocks with language:

```javascript
function greet(name) {
  console.log(`Hello, ${name}!`);
}
greet("world");
```

Triple backticks without language:

```
No syntax highlighting here.
```

Indent-based code block (4 spaces):

    SELECT *
    FROM users
    WHERE active = true;

---

## Blockquotes

> A single-level quote.
>
> - Can contain lists
> - And other Markdown

Nested quotes:

> Level 1
>> Level 2
>>> Level 3

---

## Horizontal Rules

Three or more of -, *, or _ on a line by themselves:

---

***

___

---

## Tables (GFM)

| Column A | Column B | Column C |
|:---------|:--------:|---------:|
| left     |  center  |     right|
| a        |    b     |         c|

Table with inline code and emphasis:

| Name    | Value       |
|---------|-------------|
| `alpha` | **bold**    |
| `beta`  | *italic*    |

---

## Footnotes (GFM flavor)

Here is a statement with a footnote.[^1] Another one with a second footnote.[^second]

[^1]: This is the first footnote.
[^second]: This is the second footnote.

---

## Definition Lists (GFM)

Term
: Definition of the term.

Another Term
: First definition line
: Second definition line

---

## Admonitions / Callouts (GitHub flavored)

> [!NOTE]
> This is a note callout.

> [!TIP]
> This is a tip with helpful guidance.

> [!WARNING]
> This is a warning. Proceed carefully.

---

## Emojis (GFM shortcodes)

Shortcodes like :tada: :rocket: :sparkles:

---

## Escaping and Inline HTML

Escape special characters with backslashes: \*literal asterisks\*

Inline HTML is allowed in many renderers:

<span style="color: tomato;">Colored text via HTML</span>

---

## Math (if your renderer supports it)

Inline: \( e^{i\pi} + 1 = 0 \)

Block:

\[
  \int_{-\infty}^{\infty} e^{-x^2} \, dx = \sqrt{\pi}
\]

---

## HTML Details/Summary (often supported)

<details>
  <summary>Click to expand</summary>

  Hidden content with **Markdown** inside.

  - Works on GitHub and many renderers
  - Useful for FAQs

</details>

---

## Front Matter (YAML; parser-dependent)

```
---
title: "My Document"
description: "Short description here"
tags: [docs, markdown]
---
```

---

## Escaping Backticks Inside Code

Use longer fences outside when inner code needs backticks:

````markdown
```bash
echo "`date`"
```
````

---

## Credits

This sheet targets CommonMark + GFM features widely supported across editors and viewers.