# Xiaosong Yuan — Personal Homepage

Personal academic homepage for **Xiaosong Yuan (苑小松)**, Ph.D. candidate at Jilin University.

Live page: https://yuanxs21.github.io/yuanxs/

Local preview: open `index.html` in a browser, or run `python -m http.server`.

## Stack

- Pure HTML + CSS (no build step, no framework)
- Google Fonts: *Inter*, *Newsreader*, *JetBrains Mono*
- A small inline script for the theme toggle and publication filter tabs

## Structure

```
.
├── index.html        # The whole page
├── css/
│   ├── styles.css    # Design system (light/dark, typography, layout)
│   └── avatar.svg    # SVG monogram
├── docs/
│   └── yuanxs_resume.pdf
└── slides/           # (legacy)
```

## Design

A minimal, "paper-and-ink" academic aesthetic:

- Warm off-white background with a single muted gold accent
- Newsreader serif for display, Inter for body, JetBrains Mono for metadata
- Hairline dividers, generous whitespace, sticky translucent nav
- Light/dark theme that respects system preference and is remembered in `localStorage`
- Publication list filterable by year / first-author
