# Wenlong Zhang's Academic Homepage

Personal academic website of Wenlong Zhang, Young Researcher at Shanghai AI Laboratory.

The site is built with [HugoBlox Academic CV](https://github.com/HugoBlox/theme-academic-cv) and deployed to GitHub Pages.

## Local development

Requirements:

- Hugo Extended 0.162.0
- Node.js 22+
- Go 1.23+

Install the frontend dependencies and start the development server:

```bash
npm install
hugo server
```

Build the production site and generate the search index:

```bash
npm run build
```

## Content map

- `data/authors/me.yaml`: profile, affiliations, education, experience, and links
- `content/_index.md`: homepage sections
- `content/publications/`: publication pages and citation files
- `content/projects/`: research projects
- `content/blog/`: homepage news items
- `content/service/`: academic service and teaching
- `assets/media/`: avatar and project media

The publication source BibTeX is kept in `publications.bib`. Each publication page is generated from that source and can be enriched with abstracts, images, datasets, code, or demos.
