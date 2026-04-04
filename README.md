# ArghavanAlisoltani.github.io

Personal academic website for **Arghavan (Aria) Alisoltani, PhD**.

This repository hosts a static portfolio-style site focused on:
- Bioinformatics and computational biology research
- Publications and research software/tools
- Course materials and learning resources
- Professional experience, education, and mentorship highlights

## Site structure

- `index.html` — Main homepage with profile, research focus, experience, awards, teaching, and quick links.
- `publications/publications.html` — Searchable/filterable publications page with “under development” projects.
- `tools/tools.html` — Tools and papers hub (e.g., ViralVar, FGT-DB, Coronavirus3D) plus links to active projects.
- `courses/index.html` — Learning hub linking to tutorials across microbial genomics, RNA-seq, protein structure, programming, AI, and quantum computing.
- `presentations/index.html` — Presentation index (currently minimal, with 2026 content).
- `Aria_Alisoltani_CV.pdf` — Downloadable CV.
- `profile_photo.jpeg` — Profile image used on the homepage.

## Repository contents (high level)

- `courses/` — Topic pages for training/tutorial content.
- `publications/` — Publication PDFs and publication browser page.
- `tools/` — Tool descriptions and paper PDFs connected to developed resources.
- `presentations/` — Slide-style presentation pages.
- Root-level static assets and homepage entrypoint.

## Local development

This is a plain static site (HTML/CSS/JS), so no build step is required.

### Quick preview

Open directly in a browser:
- `index.html`

or serve locally:

```bash
python3 -m http.server 8000
```

Then visit:
- `http://localhost:8000/`

## Maintenance notes

- Keep internal links relative so pages work in GitHub Pages.
- When adding new courses/tools/publications, update their corresponding index pages.
- Keep downloadable artifacts (PDFs/images) in stable paths referenced by the HTML pages.

## Deployment

Designed for GitHub Pages static hosting.

Typical deployment target:
- `https://arghavanalisoltani.github.io/`
