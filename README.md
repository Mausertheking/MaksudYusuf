# Maksud Yusuf — Portfolio

Live: **https://mausertheking.github.io/MaksudYusuf/**

Personal portfolio: research, projects, experience, awards, press coverage, football, and the road to cybersecurity.

The site is one HTML file, `index.html`, with its fonts in `fonts/` and project screenshots in `img/`. There's no build step and nothing to install. The typefaces are Newsreader (headings) and Source Sans 3 (text); the goalkeeper animation and the SHA-256 demo are hand-written.

| File | What it is |
| --- | --- |
| `index.html` | The site |
| `cop29-paper.jpg` | Page 427 of the Palestra Congress proceedings, shown in the "Read the paper" reader |
| `cop29-paper.pdf` | The same page as a PDF, for the "Download PDF" button |
| `photo.jpg` | Portrait in the hero (640 × 800) |
| `fonts/` | Newsreader and Source Sans 3 (woff2, Latin and Latin Extended) |
| `img/` | Project screenshots and Verve App Store images |

GitHub Pages publishes the `main` branch from the repository root. Changes go live about a minute after they're pushed.

## Editing

- **Projects, research and press** are data at the top of the `<script>`: the `PROJECTS`, `RESEARCH` and `PRESS` arrays. Each project and study becomes an entry on the home page and its own case-study page (`#/project/<id>` or `#/research/<id>`). To add a project, copy an entry, give it a new `id`, and add its screenshot to `MEDIA` (`phones` for app screens, `screen` for a website). `FEATURED` picks the three large rows.
- **Photo**: replace `photo.jpg` with a new 4:5 portrait under the same name.
- **About, experience, awards and toolkit** are plain HTML sections. Search for their headings.

In the local working folder the site file is named `maksudyusuf.html`; it is uploaded here as `index.html`.
