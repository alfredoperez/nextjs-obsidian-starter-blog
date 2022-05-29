---
title: Markdown Cheatsheet
date: '2022-05-20'
tags: ['markdown', 'code', 'features']
draft: false
summary: Example of a markdown file with code blocks and syntax highlighting
---

# Markdown Cheatsheet

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

#obsidian

Common  
_Emphasized text_ _Emphasized text_  
~~Strikethrough text~~  
\_Strong text\_\_ **Strong text**

**Strong emphasized text\_** or **_Strong emphasized text_**

[Named Link](http://www.google.fr/ 'Named link title') and http://www.google.fr/ or http://example.com/

Table, like this one :

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |

Adding a pipe `|` in a cell :

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell |               |

Left, right and center aligned table

| Left aligned Header | Right aligned Header | Center aligned Header |
| :------------------ | -------------------: | :-------------------: |
| Content Cell        |         Content Cell |     Content Cell      |
| Content Cell        |         Content Cell |     Content Cell      |

`code()`

```javascript
var specificLanguage\_code =
    {
        "data": {
            "lookedUpPlatform": 1,
            "query": "Kasabian+Test+Transmission",
            "lookedUpItem": {
                "name": "Test Transmission",
                "artist": "Kasabian",
                "album": "Kasabian",
                "picture": null,
                "link": "http://open.spotify.com/track/5jhJur5n4fasblLSCOcrTp"
            }
        }
    }
```

- Bullet list
  - Nested bullet
    - Sub-nested bullet etc
    - Sub-nested bullet 2
  - Nested bullet 2
    - Sub-nested bullet etc
    - Sub-nested bullet 2
- Bullet list item 2

1. A numbered list
   1. A nested numbered list
   2. Which is numbered
2. Which is numbered

- [ ] An uncompleted task
- [x] A completed task

> Blockquote
>
> > Nested blockquote

Divider

---

_Image with alt :_

![picture alt](http://via.placeholder.com/200x150 'Title is optional')

Foldable text:

<details>  
  <summary>Title 1</summary>  
  <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>  
</details>  
<details>  
  <summary>Title 2</summary>  
  <p>Content 2 Content 2 Content 2 Content 2 Content 2</p>  
</details>  
  
  
```html  
<h3>HTML</h3>  
<p> Some HTML code here </p>  
```  
  
```Typescript  
const foo = a >= b ? 5: 6;  
```  
  
Hotkey:  
<kbd>⌘F</kbd>  
<kbd>⇧⌘F</kbd>  
  
Hotkey list:  
  
| Key | Symbol |  
| --- | --- |  
| Option | ⌥ |  
| Control | ⌃ |  
| Command | ⌘ |  
| Shift | ⇧ |  
| Caps Lock | ⇪ |  
| Tab | ⇥ |  
| Esc | ⎋ |  
| Power | ⌽ |  
| Return | ↩ |  
| Delete | ⌫ |  
| Up | ↑ |  
| Down | ↓ |  
| Left | ← |  
| Right | → |  
  
Emoji: 😎  
  
## Callouts  
  
> [!INFO] > Here's a callout block. > It supports **markdown** and [[Internal link|wikilinks]].  
  
> [!FAQ]- Are callouts foldable? > Yes! In a foldable callout, the contents are hidden until it is expanded.
