# amjad-atieh.portfolio

Personal portfolio website for Amjad Atieh — software engineer, systems programmer, and 42 Amman graduate (first cohort).

## Live

> Deploy `index.html` to any static host (Netlify, GitHub Pages, Vercel, etc.) — no build step required.

## Stack

- Vanilla HTML, CSS, JavaScript — zero dependencies, zero frameworks
- [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) (headings) + [Inter](https://fonts.google.com/specimen/Inter) (body) via Google Fonts
- Canvas-generated film-grain noise texture
- Intersection Observer API for scroll-triggered animations

## Structure

```
portfolio/
└── index.html   # entire site — styles, markup, and scripts in one file
```

## Sections

| Section | Content |
|---|---|
| Hero | Name, title, bio, quick links |
| Projects | Andary (live demo), Webserv, minishell, Philosophers, cub3D, FdF |
| Skills | Languages, frameworks, tools, concepts |
| Experience | Concentrix — Client Support Specialist, Tier 2 |
| Education | 42 Amman · Tafila Technical University |
| Contact | Email, GitHub, LinkedIn |

## Running locally

```bash
# Any static file server works, e.g.:
python3 -m http.server 8080
# then open http://localhost:8080
```

Or just open `index.html` directly in a browser — it works without a server.

## Customisation

All design tokens (colors, fonts, spacing) live in the `:root` block at the top of the `<style>` tag in `index.html`. The accent color is `--accent: #d4943a` (electric amber).

## License

MIT