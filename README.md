# README

# Obsidian Vault Template

A clean, durable Obsidian setup that favors **simplicity**, **bottom-up knowledge building**, and **as-little-as-needed** plugins. It’s the exact structure I use daily for writing, research, projects, and collections like books, games, and videos.

👉 **Companion post:** [*Complete Obsidian vault guide tour*](https://bryanhogan.com/blog/obsidian-vault) - goes deeper into the philosophy and workflows behind this template.

---

## Table of contents

- [README](#readme)
- [Obsidian Vault Template](#obsidian-vault-template)
  - [Table of contents](#table-of-contents)
  - [Why this template?](#why-this-template)
  - [Quick start](#quick-start)
  - [Folder tour](#folder-tour)
  - [Core conventions](#core-conventions)
  - [Smart notes (bottom-up)](#smart-notes-bottom-up)
  - [Templates](#templates)
  - [Recommended plugins](#recommended-plugins)
  - [Common workflows](#common-workflows)
    - [Capture a new idea (Zettel)](#capture-a-new-idea-zettel)
    - [Start a project](#start-a-project)
    - [Log a book or game](#log-a-book-or-game)
    - [Draft a blog post](#draft-a-blog-post)
  - [Syncing between desktop \& mobile](#syncing-between-desktop--mobile)
  - [FAQ](#faq)
  - [Contributing \& customization](#contributing--customization)
  - [Recent changes](#recent-changes)
    - [Credits \& further reading](#credits--further-reading)

---

## Why this template?

* **Stable, future-proof**: Sticks to plain Markdown and Obsidian core features.
* **Lightweight**: Minimal folder count, minimal plugins, zero CSS snippets.
* **Bottom-up by default**: Notes grow into Maps of Content (MOCs) organically.
* **Multi-purpose**: Works for writing, research, personal projects, and collections.

If you want a vault that **helps your other work** instead of becoming the work, this is it.

---

## Quick start

1. Download my vault or clone it from the Github repo.
2. Unzip the `.zip` file to a folder of your choosing.
3. In Obsidian open the folder as a vault.

---

## Folder tour

Each top-level item is a folder:

```
01 - Note Box/       → Zettels (atomic notes), projects, and MoCs
02 - Collections/    → Subfolders: Books, Clippings, Games, etc.
03 - Temporary/      → Short-lived scratch notes
04 - Meta/           → Archive, Attachments, Bases, Templates
```

**Rules of thumb**

* Active projects & lasting knowledge → **Note Box**
* Media & lists → **Collections**
* Remove soon → **Temporary**
* Vault config & templates → **Meta**

---

## Core conventions

* **Keep it simple.**
* Prefer **one vault** over many.
* **Minimize folders**; use links, tags, and MOCs for structure.
* Stick to **standard Markdown** (future-proof).
* **Pluralize tags / links** (e.g., `[[books]]`, `[[games]]`).
* Dates in **`YYYY-MM-DD`**.

Theme: Obsidian **basic dark**.

---

## Smart notes (bottom-up)

* Notes in `01 - Note Box` **link** to related topics with `[[Wiki Links]]`.
* Topics naturally attract clusters; those clusters become **MoCs** (Map of Content).
* The pattern: Individual notes → Topic pages → MOCs.
* A **Project Template** is available for project-scoped work, those notes live in Note Box alongside everything else.
* If you’re new to this style, see the [blog’s section on smart notes / Zettelkasten](https://bryanhogan.com/blog/obsidian-vault#smart-notes-bottom-up-note-taking).

---

## Templates

Enable **Templates** (core plugin) and set the template folder to `04 - Meta/Templates`. Choose a hotkey with which to insert template (I choose `ctrl + r`)

* **Zettel Template** → `04 - Meta/Templates/Zettel Template.md`
* **MoC Template** → `04 - Meta/Templates/MoC Template.md`
* **Project Template** → `04 - Meta/Templates/Project Template.md`
* **Blog Post Template** → `04 - Meta/Templates/Blog Post Template.md`
* **Book Template** → `04 - Meta/Templates/Book Template.md`
* **Game Template** → `04 - Meta/Templates/Game Template.md`
* **Location Template** → `04 - Meta/Templates/Location Template.md`
* **Script Template** → `04 - Meta/Templates/Script Template.md`

Each template pre-fills sensible **properties** and **sections** so you can start typing immediately.

---

## Recommended plugins

I keep the list short to reduce load time and breakage risk.

* **FolderNotes** — Open a folder’s “home note” when clicking the folder.
  [https://github.com/LostPaul/obsidian-folder-notes](https://github.com/LostPaul/obsidian-folder-notes)
* **Filename Heading Sync** — Keeps the file name in sync with your first `# Heading`.
  [https://github.com/dvcrn/obsidian-filename-heading-sync](https://github.com/dvcrn/obsidian-filename-heading-sync)
* **Dataview** — Useful for inline JS tricks (e.g., linking today’s note).
  [https://github.com/blacksmithgu/obsidian-dataview](https://github.com/blacksmithgu/obsidian-dataview)
* **LanguageTool Integration** — Spell/grammar checking.
  [https://github.com/Clemens-E/obsidian-languagetool-plugin](https://github.com/Clemens-E/obsidian-languagetool-plugin)

---

## Common workflows

### Capture a new idea (Zettel)

1. `Ctrl/Cmd + R` (your hotkey) → **Insert** `Zettel Template`.
2. Link related topics with `[[Topic]]`.
3. When a cluster forms, create a **MoC** with `MoC Template`.

### Start a project

1. Create a note in `01 - Note Box/` from `Project Template`.
2. Track scope, decisions, links to related notes.
3. If the project grows, add a **MoC** to tie its notes together.

### Log a book or game

* Use the relevant template in `02 - Collections/` subfolders (`Books`, `Games`).

### Draft a blog post

* Use `Blog Post Template` in `02 - Collections/`.

---

## Syncing between desktop & mobile

This vault is plain Markdown, so you can use **any** sync (Obsidian Sync, iCloud/Drive, Dropbox, Git, etc.).
My setup:

* **Backup**: personal GitHub private repo.
* **Sync**: Google Drive (Drive for Desktop on Windows + DriveSync on Android).

For pros/cons and alternatives, see the my blog's [**how to sync Obsidian**](https://bryanhogan.com/blog/how-to-sync-obsidian) guide.

---

## FAQ

**Why one vault instead of many?**
Cross-linking is the superpower. Multiple vaults fragment knowledge and slow you down.

**Why so few folders?**
Folders are "hard" structure. Links, tag links, and MoCs stay flexible as ideas evolve.

**Do I need all the plugins?**
No. Start with **none**. Add only what solves a real problem.

**Where do attachments go?**
Configure Obsidian's attachment folder in Settings → Files & Links → Default location for new attachments.

**How do I keep titles and file names in sync without showing file names as H1?**
Disable "Show file name as title" and use **Filename Heading Sync**.

---

## Contributing & customization

* Fork the repo and adjust:
  * Rename top-level folders to your taste.
  * Edit templates in `04 - Meta/Templates/`.
  * Tweak folder overview notes and Bases.

* PRs welcome for:
  * Additional lightweight templates,
  * Better folder overviews using Bases,
  * Further small quality-of-life improvements.

If you publish your own variation, link it in a PR and I'll add a "Community Variants" list.

---

## Recent changes

* **Simplified folder structure**: Went from 6 top-level folders to 4. `Zettelkasten` → `Note Box`, `Miscellaneous` → `Meta`, and `Projects` was removed as a dedicated folder.
* **Streamlined templates**: Dropped the numbered prefix naming (e.g., `01A - Zettel.md` → `Zettel Template.md`). Added new templates: Location and Script.
* **Fewer plugins**: Cut the recommended list from 7 to 4 — removed Book Search, Home Tab, and Lazy Plugin Loader.

---

### Credits & further reading

* Companion post: [*Complete Obsidian vault guide tour*](https://bryanhogan.com/blog/obsidian-vault)
* On smart notes / Zettelkasten, MOCs, and bottom-up knowledge building ([see the blog post](https://bryanhogan.com/blog/obsidian-zettelkasten)).

> P.S. If you find this helpful, let me know!
