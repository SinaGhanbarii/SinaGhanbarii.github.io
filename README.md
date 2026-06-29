# Sina GhanbariPakdehi — Academic Website

Personal academic website built with the Hugo Blox Academic CV template and configured for GitHub Pages.

## Included content

- Academic biography and research interests
- Research overview focused on HDH desalination, modelling, sustainable process design, and data-driven engineering
- Education, research experience, teaching experience, awards, and technical skills
- Two publication records with BibTeX citation files
- Ten academic and engineering project pages
- Downloadable CV and LaTeX CV source
- GitHub Pages build and deployment workflows

## Local development

Requirements:

- Hugo Extended 0.162.0
- Node.js 22
- pnpm

Run:

```bash
pnpm install
pnpm run dev
```

Create a production build with:

```bash
pnpm run build
```

## Deploy on GitHub Pages

1. Create a GitHub repository and upload this project to its root.
2. In **Settings → Pages**, select **GitHub Actions** as the source.
3. Push to the `main` branch. The included workflow builds and deploys the site.
4. The workflow detects the correct GitHub Pages base URL automatically.

The configured `baseURL` is `https://sinaghanbarii.github.io/`. If the site is hosted elsewhere, update `config/_default/hugo.yaml`.

## Items to replace or verify

- Replace `assets/media/authors/me.png` with a professional portrait when available.
- Confirm the final publication metadata for the in-press Elsevier chapter.
- Add Google Scholar or ORCID links to `data/authors/me.yaml` when available.
- Update the repository URL in `config/_default/params.yaml` after creating the final website repository.
- Add language proficiency only when the preferred public wording is confirmed.

## CV

- Public PDF: `static/uploads/resume.pdf`
- LaTeX source: `cv/main.tex`
