# Instagram-Profile

A responsive Instagram UI built with **pure HTML & CSS** (no frameworks). It adapts its layout to the device:

- **Mobile (`< 768px`)** — top app bar + bottom navigation, full-width content.
- **Tablet (`>= 768px`)** — icon-only left sidebar navigation.
- **Desktop (`>= 1264px`)** — full labeled left sidebar with wider, centered content (real Instagram desktop structure).

## Screens

| File | Screen |
| --- | --- |
| `index.html` | Home feed (stories + posts) |
| `profile.html` | Profile (stats, highlights, post grid) |
| `explore.html` | Explore (search, filter chips, masonry grid) |

## Tech

- Semantic HTML5 (`header`, `main`, `nav`, `aside`, `article`, `section`, `dl`)
- Layout with **Flexbox** (bars, nav, post layout) and **CSS Grid** (stats, post grid, explore masonry)
- One shared stylesheet: `css/styles.css`
- Inline SVG icons (no icon fonts, no emojis)

## Run locally

```bash
npm install
npm run dev      # serves the site at http://localhost:3000
```

Or simply open `index.html` directly in a browser.

## Folder structure

```
.
├── index.html        # Home feed
├── profile.html      # Profile screen
├── explore.html      # Explore screen
├── css/
│   └── styles.css    # Shared responsive styles
└── README.md
```
