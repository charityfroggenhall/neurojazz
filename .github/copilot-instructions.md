# Copilot Instructions for NeuroJazz

## Project Overview
NeuroJazz is a cognitive framework and journaling system designed for neurodivergent minds, especially ADHD, with a focus on privacy, ethics, and non-commercial use. The project is structured as a static site (GitHub Pages/Jekyll) with Markdown-based content and custom templates.

## Key Directories & Files
- `docs/` — Main site content, Jekyll config, and assets
  - `index.md`, `about.md`, `playbook.md` — Core documentation
  - `_includes/`, `assets/` — HTML partials and static assets (CSS, images)
- `case-study/`, `examples/`, `research-threads/`, `templates/` — Thematic content and journaling templates
- `logs/` — Dated personal logs (e.g., `2025-07-27.md`)
- `robots.txt`, `LICENSE.md`, `ETHICS.md` — Site rules, licensing, and ethical guidelines

## Authoring & Content Patterns
- All content is Markdown. Use YAML frontmatter only if required by Jekyll.
- Templates in `templates/` are for new logs or research entries. Copy and adapt as needed.
- Logs are named by date (`YYYY-MM-DD.md`) and stored in `logs/`.
- Research threads are long-form, topic-focused Markdown files in `research-threads/`.
- Case studies and examples are in their respective folders, following the same Markdown structure.

## Conventions & Workflows
- **No build step required**: Content is served directly via GitHub Pages.
- **No custom plugins**: Only standard Jekyll features and Markdown.
- **Non-commercial, attribution required**: See `README.md` and `LICENSE.md` for usage restrictions.
- **AI/agent contributions**: Always preserve author attribution and respect privacy/ethics statements.
- **Do not add analytics, tracking, or external scripts**.

## Examples
- To add a new daily log: copy `templates/daily-log-template.md` to `logs/YYYY-MM-DD.md` and fill in.
- To start a new research thread: copy `templates/post-integration-template.md` to `research-threads/` and adapt.

## Ethics & Privacy
- Do not introduce features that store or process user data beyond text logs.
- Any future AI or data features must be opt-in, transparent, and privacy-first (see `ETHICS.md`).

## Integration Points
- No external APIs or dynamic backends. All content is static.
- Images and CSS are in `docs/assets/`.

---

For questions about structure or ethics, see `README.md` and `ETHICS.md`.
