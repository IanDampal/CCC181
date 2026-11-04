# CCC181 Week 10: CampusConnect Mobile-First Login Page

React + TypeScript starter for the Week 10 group activity. The page is already
built. Your group's job is the **mobile-first CSS** and the **GitHub teamwork**.

## Run it

```bash
npm install
npm run dev          # open the local URL it prints
npm run dev:phone    # same, but your phone (same Wi-Fi) can open the Network URL
npm run build        # must finish with no errors before you submit
```

## Rules

- Edit only the CSS files in `src/styles/` (one member = one file). Do not edit `reset.css`.
- Plain CSS only. No Tailwind, Bootstrap, Material UI, styled-components, or any UI library.
- Phone styles first (no media query), then `min-width` queries only. Never `max-width`.
- Do not edit the `.tsx` files or rename classes. If you must, tell the group first.

## Group information (fill in)

| Item | Your answer |
| --- | --- |
| Group number | 9 |
| Section | IT3 - A|
| Repository URL |https://github.com/IanDampal/CCC181/edit/main/README.md |

## Members (each member fills in their own row in their own commit)

| Member | Name | GitHub username | CSS file | What I did |
| --- | --- | --- | --- | --- |
| 1 | Kirtz Darwin D. Federico | kirtzdarwinfedrico | `base.css` | Styled the page layout, container and brand panel with CSS Grid, mobile-first. The login layout becomes two columns at 1024px, and the container is centered at 1200px. |
| 2 | Ian Clifford G. Dampal| IanDampal | `nav.css`, `index.html` | Styled the navbar with Flexbox and the footer with CSS Grid. Added the viewport meta tag and linked the CSS files in index.html. |
| 3 | Rumer V. Abriol| rumerzzzzz | `form.css` | Styled the login card, form fields and buttons with Flexbox. All tap targets are at least 48px, and the buttons and options sit side by side from 768px. |

## Experiment 0: the page without the viewport tag

What did the page look like in DevTools phone mode **before** adding the viewport meta tag?
What changed **after** adding it?

> (write your answer here)

## DevTools test results

| Width | What must be true | Pass? |
| --- | --- | --- |
| 360 px | 1 column. Nav links stacked and 48px tall. Options and buttons stacked. Footer in 1 column. No sideways scrollbar. | YES |
| 768 px | Nav in one row (brand left, links right). Checkbox and link in one row. Two buttons side by side. | YES |
| 1024 px | Brand panel and login card side by side. Footer in 3 columns. Heading is larger. | YES |
| 1280 px | Content centered and stops at 1200px. | YES |

### Breakpoints I observed

Using **Show media queries** and dragging slowly from 360 px to 1280 px, the layout changed at these exact widths:

> (write the widths here, and say whether any width looked broken)

Screenshots are in `screenshots/` as `360.png`, `768.png`, `1024.png`, `1280.png`.

## What our group learned (leader writes this last)

> (write your answer here)
