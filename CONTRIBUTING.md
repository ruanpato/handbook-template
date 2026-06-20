# Contributing

Thanks for helping improve this handbook.

## Principles

- **One concept = one file** under `content/<lang>/{modules,labs,projects}/`, numbered for order.
- **Bilingual parity (if multilingual):** the same relative path/filename must exist in every
  `content/<lang>/`. Translate the **content**, never the filename.
- **Portable Markdown:** CommonMark/GFM; avoid renderer-specific HTML; relative internal links.
- **Front matter** on every module/lab/project (see `templates/`).
- **Verified references:** access each link before adding it; record date/version.
- **Ethics (topic-dependent):** any offensive/hazardous technique stays lab-only and authorized,
  with mitigation/detection. See `SECURITY.md`.

## Workflow

1. Copy the relevant file from `templates/` into `content/<lang>/...`.
2. Keep headings/structure identical across languages.
3. Run the checks locally if you have them; CI runs lint, spell, links, build, parity.
4. Commit with **Conventional Commits** (`feat:`, `fix:`, `docs:`, `ci:`, `chore:`).

## Commit messages

`type(scope): summary` — e.g., `docs(modules): add 03-tools (en/pt-BR)`.
