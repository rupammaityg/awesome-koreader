# Contributing to Awesome KOReader

Thank you for your interest in contributing! This is a community-driven project and every contribution makes it more valuable for KOReader users worldwide.

## Table of Contents

- [What belongs here](#what-belongs-here)
- [What does NOT belong here](#what-does-not-belong-here)
- [How to contribute](#how-to-contribute)
- [Quality standards](#quality-standards)
- [Entry format](#entry-format)
- [Adding a new category](#adding-a-new-category)
- [Reporting outdated or broken links](#reporting-outdated-or-broken-links)

---

## What belongs here

- **Plugins** (`.koplugin`) — Lua plugins that extend KOReader's functionality
- **User Patches** — Lua patches placed in `koreader/patches/`
- **Sync Servers** — Self-hosted backends compatible with KOReader's sync protocol
- **Desktop Tools** — Companion apps that work with KOReader data (highlights, stats, etc.)
- **Calibre Plugins** — Calibre add-ons that interact with KOReader metadata or sync
- **Scripts & Automation** — Shell or Python tools that automate KOReader workflows
- **Themes & Icons** — Visual customization resources
- **Guides & Tutorials** — High-quality written or video content about KOReader usage or development
- **Community Resources** — Forums, subreddits, chat groups focused on KOReader

---

## What does NOT belong here

- Projects that are **abandoned** (no commits in 2+ years, known to be broken) — unless historically significant
- **Forks** with no meaningful changes over the original
- Low-quality or incomplete projects with no documentation
- Projects unrelated to KOReader
- Personal configs or dotfiles without reusable components

---

## How to contribute

### Via Pull Request (preferred)

1. **Fork** this repository.
2. **Create a branch** from `main`:
   ```bash
   git checkout -b add/my-awesome-plugin
   ```
3. **Edit** `README.md` — add your entry in the correct category, in alphabetical order within that category where possible.
4. **Commit** your change with a clear message:
   ```bash
   git commit -m "Add my-plugin: short description of what it does"
   ```
5. **Open a Pull Request** against `main` with the PR template filled out.

### Via Issue

If you don't want to open a PR, [open an issue](../../issues/new/choose) using the **"Add Resource"** template. A maintainer will add it.

---

## Quality standards

Before submitting, please ensure:

- [ ] The project is publicly accessible (GitHub, GitLab, etc.)
- [ ] It has a `README.md` with at least a basic description and install instructions
- [ ] It works with a recent version of KOReader (or the compatible version is noted)
- [ ] The link is to the primary/canonical source, not a mirror or fork
- [ ] You are not the author submitting your own project *without disclosing it* — self-promotion is welcome but please note it in your PR description
- [ ] The entry is placed in the most appropriate category

---

## Entry format

Each entry should follow this format:

```markdown
- [project-name](https://github.com/author/repo) - One-sentence description. ⭐ Star count (optional)
```

**Rules:**
- Description starts with a capital letter and ends with a period.
- Keep descriptions concise — one sentence max, focus on what the user gets.
- Star counts are optional but helpful for popular projects. Update them when they're significantly off.
- If a project fits multiple categories, list it in the **most specific** one. A brief mention in a second category is acceptable for highly cross-cutting tools.

**Example:**

```markdown
- [anki.koplugin](https://github.com/Ajatt-Tools/anki.koplugin) - Generate Anki flashcards from words looked up in KOReader's built-in dictionary. Works with AnkiConnect. ⭐ 179+
```

---

## Adding a new category

If your contribution doesn't fit an existing category:

1. Propose the new category in your PR description and explain why it warrants its own section.
2. A category should have **at least 3 entries** to justify its own section. If you only have one entry, place it in the most closely related existing category and note in your PR that the category may be worth creating later.
3. Add the category to the **Contents** table of contents at the top of `README.md` as well.

---

## Reporting outdated or broken links

- Open an issue using the **"Broken Link / Outdated Entry"** template.
- Or submit a PR directly removing or updating the entry.

---

## Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to uphold it. Report unacceptable behavior to the project maintainers via GitHub Issues.

---

Thank you for helping make **Awesome KOReader** the best resource for the KOReader community!
