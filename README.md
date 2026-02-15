# Web Development Collections

## HTML-CSS

### CSS

**Specificity**

**Specificity** is an algorithm that calculates the weight that is applied to a given CSS declaration

1. Inline CSS (style attribute)
2. ID #
3. Class .
4. Element

---

**Styling Links**

- `a:link`: Normal unvisited link
- `a:hover`: Link when hovered
- `a:active`: Moment link is clicked
- `a:focus`: Moment link receives focus
- `a:visited`: Link user has visited

---

**Box Model**

- Content - Text, images, etc
- Padding - Space between content and border
- Border - Separates the padding & margin
- Margin - Space outside of border

---

**Typical Breakpoints**

- **576px** - Smartphones
- **768px** - Tablets
- **992px** - Desktop
- **1024px** - Landscape
- **1200px** - Desktop/Widescreen

### JavaScript

**What is the Document Object Model?**

- Programming interface for web/html elements
- Structure that we can interact with via JavaScript
- Includes tags, attributes, text nodes, etc
- Representated as a tree structure

**DOM Visualization**

```bash
flowchart TD
  DOC[Document]
  HTML[html]
  HEAD[head]
  BODY[body]

  TITLE[title]
  META[meta]
  LINK[link]

  HEADER[header]
  MAIN[main]
  FOOTER[footer]

  H1[h1]
  NAV[nav]
  SECTION[section]
  ARTICLE[article]
  ASIDE[aside]

  P[p]
  DIV[div]
  UL[ul]
  LI1[li]
  LI2[li]
  A[a]
  IMG[img]

  DOC --> HTML
  HTML --> HEAD
  HTML --> BODY

  HEAD --> META
  HEAD --> LINK
  HEAD --> TITLE

  BODY --> HEADER
  BODY --> MAIN
  BODY --> FOOTER

  HEADER --> H1
  HEADER --> NAV

  MAIN --> SECTION
  MAIN --> ARTICLE
  MAIN --> ASIDE

  ARTICLE --> P
  ARTICLE --> DIV

  DIV --> UL
  UL --> LI1
  UL --> LI2
  LI1 --> A
  LI2 --> IMG

```
