# Susy P Verghese — Portfolio

A minimal personal portfolio made with **HTML and CSS only** (no JavaScript), for the Unit V practical assignment.

## Structure

```
index.html   One scrolling page: Home (name, photo, intro, navigation) ·
             About me (description, education, interests & hobbies) ·
             Skills · Projects · Contact form
style.css    All styling — colours, fonts, layout, responsive rules, animations
images/      Profile photo and project artwork
```

Open `index.html` in any browser to view it.

## Colours

| Shade        | Hex       | Used for                      |
| ------------ | --------- | ----------------------------- |
| Light brown  | `#f3ece3` / `#e8dccd` | Page background, cards |
| Mid brown    | `#a3846a` | Photo frame, details          |
| Dark brown   | `#2b1d16` | Text, footer, one project card |
| Light purple | `#d9cbf2` | Highlights, hover states, cards |
| Mid purple   | `#6a4f9a` | Small labels                  |
| Dark purple  | `#33215a` | Buttons, accents, contact area |

## Still to fill in

- **Social links** in the contact section.

## Scroll animations (CSS only)

Built with CSS scroll-driven animations (`animation-timeline`): a reading-progress bar under the header, the hero drifting away, sections and list rows rising in one after another, project pictures settling from a slight zoom, and project cards shrinking back as the next one stacks on top. Supported in Chrome, Edge, Opera and Safari 26+; other browsers show the page without these effects. Turned off for visitors who prefer reduced motion.

The contact form uses `mailto:`, so pressing *Send message* opens the visitor's email app.
