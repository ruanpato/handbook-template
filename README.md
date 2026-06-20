# Handbook Template

![Status](https://img.shields.io/badge/status-template-blue) [![Docs](https://img.shields.io/badge/docs-GitHub%20Pages-555.svg)](https://ruanpato.com/handbook-template/)
[![Content: CC BY 4.0](https://img.shields.io/badge/content-CC%20BY%204.0-blue.svg)](LICENSE)
[![Code: MIT](https://img.shields.io/badge/code-MIT-green.svg)](LICENSE-CODE)

🌐 **Language / Idioma:** **[English](content/en/index.md)** · **[Português (BR)](content/pt-BR/index.md)**

> A reusable, **GitHub-readable-first** template for bilingual technical handbooks: a MkDocs/
> GitHub Pages site, future PDF/book base, and a clone-and-go structure for any topic
> (cybersecurity, ML, GenAI, DS&A, cloud, software engineering, …). The `content/` below is
> **example scaffolding** — replace it with your topic.

This repository is, at once, a **readable GitHub handbook**, a **MkDocs/GitHub Pages site**, and a
base that can later become a **PDF/book/course**. Content lives in `content/<lang>/`; the raw
Markdown is fully readable here without building anything.

## Start here

- **English:** [content/en/index.md](content/en/index.md) · [Roadmap](content/en/roadmap.md)
- **Português:** [content/pt-BR/index.md](content/pt-BR/index.md) · [Roteiro](content/pt-BR/roadmap.md)

## Repository layout

```text
content/<lang>/   modules, labs, projects, roadmap, glossary, references, career
templates/        copy-paste scaffolds (module / lab / project)
assets/           shared images/diagrams
.github/          CI, deploy, issue/PR templates
mkdocs.yml        site config (docs_dir: content)
```

## Using this template

1. Click **Use this template** on GitHub (or clone) and rename.
2. Fill `mkdocs.yml`, `CITATION.cff`, license author/year, and this README.
3. Replace `content/en/*` (and `content/pt-BR/*` if bilingual) with your topic.
   Keep **identical relative filenames** across languages.
4. Single-language project? Delete `content/pt-BR/` and the `i18n` block in `mkdocs.yml`.
5. See [CONTRIBUTING.md](CONTRIBUTING.md) and [STYLE_GUIDE.md](STYLE_GUIDE.md).

**License:** content under **CC BY 4.0** ([LICENSE](LICENSE)); code under **MIT** ([LICENSE-CODE](LICENSE-CODE)).
