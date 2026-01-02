# Odoo – Web Design Exercise

## Overview

This project is a static implementation of the provided Odoo landing page mock-up.
The goal was to deliver a clean, maintainable and production-oriented solution,
using Bootstrap as the primary layout system and custom SCSS.

## The focus is clarity, consistency and scalability. The result is not a pixel-perfect copy, but a faithful and practical implementation aligned with real-world frontend workflows and long-term maintainability.

## Tech Stack

- HTML5 (semantic, accessible)
- Bootstrap 5.3.8
- SCSS (compiled to CSS)
- Bootstrap Icons

---

## Project Structure

```text
assets
│ ├── \*.svg
├── css
│ ├── main.css
│ └── main.css.map
└── scss
├── \_components.scss
├── \_layout.scss
├── main.scss
├── \_sections.scss
└── \_variables.scss
├── index.html
├── README.md
```

---

## How to Run

0. No build step is required.
1. Clone the repository
   git clone https://github.com/PerlaGCastillo/odooDesignExercise.git
   or
   git clone git@github.com:PerlaGCastillo/odooDesignExercise.git

2. Open `index.html` in your favorite browser

If you want to recompile or make SCSS changes:

# install:

- globally
  `npm i -g sass`
- localy
  `npm i -D sass`
- run it!
  `sass scss/main.scss css/main.css --watch`
  or just compile it!
- `sass scss/main.scss css/main.css`

---
