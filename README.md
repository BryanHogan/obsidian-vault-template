# README

# Obsidian Vault Template

A clean, durable Obsidian setup that favors **simplicity**, **bottom-up knowledge building**, and **as-little-as-needed** plugins. It's the exact structure I use daily for writing, research, projects, and collections like books, games, and videos.

**Companion post:** [*Obsidian vault setup tour*](https://bryanhogan.com/blog/obsidian-vault) - goes deeper into the setup and ideas behind this template.


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
  - [Navigation \& Bases](#navigation--bases)
  - [Templates](#templates)
  - [Recommended plugins](#recommended-plugins)
  - [Common workflows](#common-workflows)
    - [Capture a new insight (Zettel)](#capture-a-new-insight-zettel)
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
01 - Note Box/           → Zettels, projects, blog posts, scripts, locations, and MoCs
02 - Collections/        → Subfolders: Books, Clippings, Games
03 - Tasks & Reminders/  → Monthly task notes
04 - Temporary/          → Short-lived scratch notes
05 - Meta/               → Archive, Attachments, Bases, Templates
```

**Rules of thumb**

* Knowledge notes, projects & writing → **Note Box**
* Media & external content → **Collections**
* Things to get done this month → **Tasks & Reminders**
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

The `01 - Note Box` folder is the most important folder in the vault. It contains:

* **Zettel notes** - long-lasting knowledge notes that explain one concept (atomic) and **link** to related topics with `[[Wiki Links]]`.
* **Project notes** - notes belonging to a project or problem that can end.
* **Blog posts, scripts, locations** - other note types that also live here alongside everything else.

Topics naturally attract clusters; those clusters become **MoCs** (Map of Content). The pattern: Individual notes → Topic pages → MOCs. Project notes show up in project overviews (using Bases) when they are of type `Project`.

If you're new to this style, see the [blog's section on smart notes / Zettelkasten](https://bryanhogan.com/blog/obsidian-vault#smart-notes-bottom-up-note-taking).

---

## Navigation & Bases

Obsidian [Bases](https://help.obsidian.md/bases) let you display notes in table, list, or card views with filtering and sorting.

This vault uses Bases in combination with the **FolderNotes** plugin to create overview pages. Clicking on `01 - Note Box` or `02 - Collections` opens a folder note that includes Bases listing all relevant MOCs, active projects, and other content — ending with a complete list of all notes in that folder.

Between in-note links, MOCs with Bases, and Obsidian's built-in search, relevant information doesn't get lost.

---

## Templates

Enable **Templates** (core plugin) and set the template folder to `05 - Meta/Templates`. Choose a hotkey with which to insert a template (I use `Ctrl + R`).

Templates used in **Note Box**: `Zettel`, `Project`, `Blog Post`, `MoC`, `Script`
Templates used in **Collections**: `Book`, `Game`
Templates used in **Tasks & Reminders**: `Tasks & Reminders`

Additional utility templates: `Location`, `Incoming Links Base Template`, `iFrame Snippet`.

Each template pre-fills sensible **properties** and **sections** so you can start typing immediately.

---

## Recommended plugins

I keep the list short to reduce load time and breakage risk.

* **FolderNotes** — Open a folder's "home note" when clicking the folder.
  [https://github.com/LostPaul/obsidian-folder-notes](https://github.com/LostPaul/obsidian-folder-notes)
* **Filename Heading Sync** — Keeps the file name in sync with your first `# Heading`.
  [https://github.com/dvcrn/obsidian-filename-heading-sync](https://github.com/dvcrn/obsidian-filename-heading-sync)
* **LanguageTool Integration** — Spell/grammar checking.
  [https://github.com/Clemens-E/obsidian-languagetool-plugin](https://github.com/Clemens-E/obsidian-languagetool-plugin)
* **Periodic Notes** — For monthly Tasks & Reminders notes.
  [https://github.com/liamcain/obsidian-periodic-notes](https://github.com/liamcain/obsidian-periodic-notes)

---

## Common workflows

### Capture a new insight (Zettel)

1. `Ctrl/Cmd + O` type name → create if it's a new note → **Insert** `Zettel Template`.
2. Link related topics with `[[Topic]]`.
3. When a cluster forms, create a **MoC** with `MoC Template`.

### Start a project

1. Create a note in `01 - Note Box/` from `Project Template`.
2. Track scope, decisions, links to related notes.
3. If the project grows, add a **MoC** to tie its notes together.

### Log a book or game

* Use the relevant template in `02 - Collections/` subfolders (`Books`, `Games`).

### Draft a blog post

* Use `Blog Post Template` in `01 - Note Box/`.

---

## Syncing between desktop & mobile

This vault is plain Markdown, so you can use **any** sync (Obsidian Sync, iCloud/Drive, Dropbox, Git, etc.).
My setup:

* **Backup**: personal GitHub private repo.
* **Sync**: Google Drive (Drive for Desktop on Windows + DriveSync on Android).

For pros/cons and alternatives, see my blog's [**how to sync Obsidian**](https://bryanhogan.com/blog/how-to-sync-obsidian) guide.

---

## FAQ

**Why one vault instead of many?**
Cross-linking is the superpower. Multiple vaults fragment knowledge and slow you down.

**Why so few folders?**
Folders are "hard" structure. Links, tag links, and MoCs stay flexible as ideas evolve.

**Do I need all the plugins?**
No. Start with **none**. Add only what solves a real problem.

**How do I keep titles and file names in sync without showing file names as H1?**
Disable "Show file name as title" and use **Filename Heading Sync**.

---

## Contributing & customization

* Fork the repo and adjust:
  * Rename top-level folders to your taste.
  * Edit templates in `05 - Meta/Templates/`.
  * Tweak folder overview notes and Bases.

* PRs welcome for:
  * Additional lightweight templates,
  * Better folder overviews using Bases,
  * Further small quality-of-life improvements.

If you publish your own variation, link it in a PR and I'll add a "Community Variants" list.

---

## Recent changes

**Version 2.0:**

* **Updated folder structure**: Went from 4 top-level folders to 5. Added `03 - Tasks & Reminders` for monthly task notes. `Temporary` and `Meta` renumbered to `04` and `05`.
* **Heavier use of Bases**: Replaced Dataview with Obsidian's built-in Bases for creating overviews and structure throughout the vault.
* **Updated plugins**: Removed Dataview, added Periodic Notes for monthly task notes.
* **Updated templates and properties**: All templates updated with streamlined properties. Added `Tasks & Reminders` template.

**Previous:**

* **Simplified folder structure**: Went from 6 top-level folders to 4. `Zettelkasten` → `Note Box`, `Miscellaneous` → `Meta`, and `Projects` was removed as a dedicated folder.
* **Streamlined templates**: Dropped the numbered prefix naming (e.g., `01A - Zettel.md` → `Zettel Template.md`). Added new templates: Location and Script.
* **Fewer plugins**: Cut the recommended list from 7 to 4 — removed Book Search, Home Tab, and Lazy Plugin Loader.

---

### Credits & further reading

* Companion post: [*Obsidian vault setup tour*](https://bryanhogan.com/blog/obsidian-vault)
* On smart notes / Zettelkasten, MOCs, and bottom-up knowledge building ([see the blog post](https://bryanhogan.com/blog/obsidian-zettelkasten)).

> P.S. If you find this helpful, let me know!
