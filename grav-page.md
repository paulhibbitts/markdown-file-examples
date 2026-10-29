---
title: 'Portable Content Test'
url: 'http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/portable-content-test'
markdown: 'http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/portable-content-test.md'
date: '2026-10-29'
description: "A test page for content that should look the same here, in this page's Markdown version (add .md to its address) and in Docsify-This: callouts, LaTeX math and Mermaid diagrams. Callouts Note A note, for useful background. It can hold bold, italics, code and a link. Tip A tip, with a list: …"
taxonomy:
  archives_month:
    - oct_2026
  archives_year:
    - '2026'
---

# Portable Content Test

A test page for content that should look the same here, in this page's Markdown version (add `.md` to its address) and in Docsify-This: callouts, LaTeX math and Mermaid diagrams.

## Callouts

> [!NOTE]
> 
> A note, for useful background. It can hold **bold**, *italics*, `code` and [a link](https://docsify-this.net).

> [!TIP]
> 
> A tip, with a list:
> 
> - Write once in Markdown
> - Show it anywhere
> - Let others reuse it

> [!IMPORTANT]
> 
> Something readers shouldn't miss, over two paragraphs.
> 
> This is the second paragraph.

> [!WARNING]
> 
> A warning, with a numbered list:
> 
> 1. Keep a copy of your files
> 2. Check the licence before you reuse

> [!CAUTION]
> 
> A caution, for actions that can't be undone.

## Callout Shortcodes

The theme's callout shortcodes, as in Grav Helios Open Reader. Each draws a callout box of one of the five types, with its own heading.

> [!TIP]
> 
> **Learning Objectives**
> 
> - Write content once, in Markdown
> - Show it in more than one place

> [!NOTE]
> 
> **Key Takeaways**
> 
> Plain Markdown keeps content portable.

> [!TIP]
> 
> **Reflection**
> 
> Where else could this page be useful?

> [!NOTE]
> 
> **Open Educational Resources**
> 
> Teaching and learning materials that anyone can keep, reuse, revise, remix and share.

> [!IMPORTANT]
> 
> **Example**
> 
> A guide written once, shown on a Grav site, in an LMS and in Docsify-This.

> [!CAUTION]
> 
> **Case Study**
> 
> A course that moved from an LMS to an open site, without rewriting its pages.

> [!WARNING]
> 
> **Project Brief**
> 
> Turn one chapter of an open textbook into a short guide.

> [!NOTE]
> 
> **Process Note**
> 
> This page was checked in Grav, its Markdown version and Docsify-This.

> [!IMPORTANT]
> 
> **Feedback Requested**
> 
> Does every box below look right in each place?

> [!IMPORTANT]
> 
> **Announcement**
> 
> An announcement, as Important by default.

> [!NOTE]
> 
> **Class Cancelled**
> 
> An announcement as a Note, with its own heading.

> [!TIP]
> 
> **Interactive Activity**
> 
> [Open Interactive Activity ](https://h5p.org/node/1291)
> 
> Try the activity, then come back to this page.

References

- Wiley, D. (2014). *The Access Compromise and the 5th R*.
- Hibbitts, P. (2026). *Read, Move, Reuse*.

> Open content belongs to the people who write it.

## Markdown Notices

The Markdown Notices plugin's boxes, written with one to four `!` at the start of a line:

A yellow notice, with a single `!`.

A red notice, with two.

A blue notice, with three.

A green notice, with four.

## LaTeX Math

Within a sentence: the area of a circle is $A = \pi r^2$, and the average of $x_1$ to $x_n$ is $\bar{x}$. Prices such as $5 and $10 stay as text.

A block:

$$ \bar{x} = \frac{1}{n} \sum_{i=1}^{n} x_i $$

Steps lined up, with `\\` for new lines:

$$ \begin{aligned} (a + b)^2 &= (a + b)(a + b) \\ &= a^2 + 2ab + b^2 \end{aligned} $$

A matrix and chemistry: $\begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}$ and $\ce{2H2 + O2 -> 2H2O}$.

A math block:

$$ e^{i\pi} + 1 = 0 $$

## Math Inside a Callout

> [!TIP]
> 
> The quadratic formula solves $ax^2 + bx + c = 0$:
> 
> $$ x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$

> [!NOTE]
> 
> Steps lined up inside a callout, with `\\` for new lines:
> 
> $$ \begin{aligned} (a - b)^2 &= (a - b)(a - b) \\ &= a^2 - 2ab + b^2 \end{aligned} $$
> 
> And within a sentence: $$ \sum_{i=1}^{n} i = \frac{n(n+1)}{2} $$ and on it goes.

## Mermaid Diagrams

A flowchart:

```mermaid
flowchart LR
    A[Write in Markdown] --> B[Publish with Grav]
    B --> C[Markdown version]
    C --> D[Docsify-This]
    C --> E[GitHub or Codeberg]
```

A sequence diagram:

```mermaid
sequenceDiagram
    participant Author
    participant Grav
    participant Reader
    Author->>Grav: Save a page
    Reader->>Grav: Ask for page.md
    Grav-->>Reader: The page as Markdown
```

A pie chart:

```mermaid
pie title Time spent
    "Writing" : 50
    "Reviewing" : 30
    "Publishing" : 20
```

## Code Stays Code

`$x$`, `> [!NOTE]` and this block are code, so nothing in them is drawn:

```markdown
> [!NOTE]
> A callout written in Markdown, with $x^2$ math.
```

---

## Navigation

- Previous: [Read Me](http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/readme.md)
- Next: [Search](http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/search.md)
