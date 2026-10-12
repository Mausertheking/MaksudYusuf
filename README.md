# Maksud Yusuf — Portfolio

Live: **https://mausertheking.github.io/MaksudYusuf/**

Personal portfolio: research, projects, experience, awards, press coverage, football, and the road to cybersecurity.

The whole site is one self-contained file, `index.html`. There's no build step and nothing to install. All CSS, JavaScript and the Space Mono font are inline; the goalkeeper animation and the SHA-256 demo are hand-written.

| File | What it is |
| --- | --- |
| `index.html` | The site |
| `cop29-paper.jpg` | Page 427 of the Palestra Congress proceedings, shown in the "Read the paper" reader |
| `cop29-paper.pdf` | The same page as a PDF, for the "Download PDF" button |

GitHub Pages publishes the `main` branch from the repository root. Changes go live about a minute after they're pushed.

## Editing

- **Projects, research and press** are data at the top of the `<script>`: the `PROJECTS`, `RESEARCH` and `PRESS` arrays. Each project and study becomes a card on the home page and its own case-study page (`#/project/<id>` or `#/research/<id>`). To add a project, copy an entry, give it a new `id`, and pick a cover `motif` from `MOTIFS`.
- **Photo**: search for `portrait` and put `<img src="photo.jpg" alt="Maksud Yusuf">` inside that block, then upload the photo next to `index.html`.
- **About, experience, awards and toolkit** are plain HTML sections. Search for their headings.

In the local working folder the site file is named `maksudyusuf.html`; it is uploaded here as `index.html`.
