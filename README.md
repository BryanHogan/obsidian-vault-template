# Obsidian Vault Template

A clean, durable Obsidian setup that favors **simplicity**, **bottom-up knowledge building**, and **as-little-as-needed** plugins. It’s the exact structure I use daily for writing, research, projects, and collections like books, games, and videos.

👉 **Companion post:** [*Complete Obsidian vault guide tour*](https://bryanhogan.com/blog/obsidian-vault) - goes deeper into the philosophy and workflows behind this template.

---

## Table of contents

* [Why this template?](#why-this-template)
* [Quick start](#quick-start)
* [Folder tour](#folder-tour)
* [Core conventions](#core-conventions)
* [Smart notes (bottom-up)](#smart-notes-bottom-up)
* [Templates](#templates)
* [Recommended plugins](#recommended-plugins)
* [Bases + Folder overviews](#bases--folder-overviews)
* [Common workflows](#common-workflows)
* [Syncing between desktop & mobile](#syncing-between-desktop--mobile)
* [FAQ](#faq)
* [Contributing & customization](#contributing--customization)
* [License](#license)

---

## Why this template?

* **Stable, future-proof**: Sticks to plain Markdown and Obsidian core features.
* **Lightweight**: Minimal folder count, minimal plugins, zero CSS snippets.
* **Bottom-up by default**: Notes grow into Maps of Content (MOCs) organically.
* **Multi-purpose**: Works for writing, research, personal projects, and collections.

If you want a vault that **helps your other work** instead of becoming the work, this is it.

---

## Quick start

1. **Use this as a template**

   * Click **Use this template** on GitHub or clone the repo.
   * Open the folder in **Obsidian** (File → Open vault → Select folder).

2. **Enable core features**

   * Settings → *Core plugins*: **Templates**, **Properties**, **Daily notes** (optional).
   * Settings → *Templates*:
     * Add a **hotkey** for “Insert template”.

3. **(Optional) Install recommended community plugins**
   See [Recommended plugins](#recommended-plugins).

4. **Start from the folder home notes**

   * Open `01 - Zettelkasten/` and `02 - Projects/` to see their overview notes.
   * Create your first Zettel with the **Zettel Template**.

---

## Folder tour

Each top-level item is a folder:

```
00 - Bases/                → Saved Bases (Obsidian’s native views) & configs
01 - Zettelkasten/         → Evergreen “knowledge” notes (long-term)
02 - Projects/             → Project/problem notes (bounded, may end)
03 - Collections/          → Subfolders: Blog, Books, Clippings, Games, Videos
04 - Temp Notes/           → Short-lived scratch notes
05 - Miscellaneous/        → Archive, Attachments, Templates, Someday Notes
```

**Rules of thumb**

* Knowledge that should last → **Zettelkasten**
* Work that has a lifecycle → **Projects**
* Media & lists → **Collections**
* One-off / scratch → **Temp Notes**

---

## Core conventions

* **Keep it simple.**
* Prefer **one vault** over many.
* **Minimize folders**; use links, tags, and MOCs for structure.
* Stick to **standard Markdown** (future-proof).
* **Pluralize tags** (e.g., `#books`, `#projects`).
* Dates in **`YYYY-MM-DD`**.

Theme: Obsidian **basic dark**.

---

## Smart notes (bottom-up)

* Zettels and project notes **link** to related topics with `[[Wiki Links]]`.
* Topics naturally attract clusters; those clusters become **MOCs** (Map of Content).
* Both `01 - Zettelkasten` and `02 - Projects` use the **same pattern**:

  * Individual notes → Topic pages → MOCs.
* If you’re new to this style, see the [blog's section on smart notes / Zettelkasten](https://bryanhogan.com/blog/obsidian-vault#smart-notes-bottom-up-note-taking).

---

## Templates

Enable **Templates** (core plugin) and set the template folder to `05 - Miscellaneous/Templates`.

* **Zettel Template** → `05 - Miscellaneous/Templates/01A - Zettel.md`
* **Zettel MOC Template** → `05 - Miscellaneous/Templates/01B - Zettel MOC.md`
* **Project Note Template** → `05 - Miscellaneous/Templates/02A - Project Note.md`
* **Project MOC Template** → `05 - Miscellaneous/Templates/02B - Project MOC.md`
* **Blog Post Template** → `05 - Miscellaneous/Templates/03A - Blog Post.md`
* **Book Template** → `05 - Miscellaneous/Templates/03B - Book.md`
* **Game Template** → `05 - Miscellaneous/Templates/03C - Game.md`
* **Video Template** → `05 - Miscellaneous/Templates/03D - Video.md`

Each template pre-fills sensible **properties** and **sections** so you can start typing immediately.

---

## Recommended plugins

I keep the list short to reduce load time and breakage risk.

* **FolderNotes** — Open a folder’s “home note” when clicking the folder.
  [https://github.com/LostPaul/obsidian-folder-notes](https://github.com/LostPaul/obsidian-folder-notes)
* **Filename Heading Sync** — Keeps the file name in sync with your first `# Heading`.
  [https://github.com/dvcrn/obsidian-filename-heading-sync](https://github.com/dvcrn/obsidian-filename-heading-sync)
* **Dataview** — Still useful for a few inline JS tricks (e.g., linking today’s note).
  [https://github.com/blacksmithgu/obsidian-dataview](https://github.com/blacksmithgu/obsidian-dataview)
* **Book Search** — Fast create book notes with covers & metadata.
  [https://github.com/anpigon/obsidian-book-search-plugin](https://github.com/anpigon/obsidian-book-search-plugin)
* **Home Tab** — Adds a useful search field on empty tabs.
  [https://github.com/olrenso/obsidian-home-tab](https://github.com/olrenso/obsidian-home-tab)
* **LanguageTool Integration** — Spell/grammar checking.
  [https://github.com/Clemens-E/obsidian-languagetool-plugin](https://github.com/Clemens-E/obsidian-languagetool-plugin)
* **Lazy Plugin Loader** — Delay heavy plugins to speed up startup (great on mobile).
  [https://github.com/alangrainger/obsidian-lazy-plugins](https://github.com/alangrainger/obsidian-lazy-plugins)

---

## Bases + folder overviews

* **Bases** (core feature) let you build **table/card** views with filters and sorts.
* This template pairs Bases with **FolderNotes** to give each key folder a helpful **overview note**:

  * Zettelkasten overview: MOCs first, then topical entry points, then all notes.
  * Projects overview: Active projects first, then supporting artifacts.

Open `01 - Zettelkasten/` and `02 - Projects/` to see examples and start customizing.

---

## Common workflows

### Capture a new idea (Zettel)

1. `Ctrl/Cmd + T` (your hotkey) → **Insert** `01A - Zettel` template.
2. Link related topics with `[[Topic]]`.
3. When a cluster forms, create a **Zettel MOC** with `01B - Zettel MOC`.

### Start a project

1. Create a note in `02 - Projects/` from `02A - Project Note`.
2. Track scope, decisions, links to related Zettels.
3. If the project grows, add a **Project MOC** (`02B - Project MOC`).

### Log a book / game / video

* Use the relevant template in `03 - Collections/` subfolders.
* Add metadata and links to related Zettels (e.g., `[[Korean]]`, `[[Design Management]]`).

### Draft a blog post

* Use `03A - Blog Post` in `03 - Collections/Blog/`.
* When publishing to a site (e.g., Astro), you can export or point your site to this folder.

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
Folders are "hard" structure. Links, tag links, and MOCs stay flexible as ideas evolve.

**Do I need all the plugins?**
No. Start with **none**. Add only what solves a real problem.

**Where do attachments go?**
`05 - Miscellaneous/Attachments/` keeps binaries in one place.

**How do I keep titles and file names in sync without showing file names as H1?**
Disable "Show file name as title" and use **Filename Heading Sync**.

---

## Contributing & customization

* Fork the repo and adjust:
  * Rename top-level folders to your taste.
  * Edit templates in `05 - Miscellaneous/Templates/`.
  * Tweak folder overview notes and Bases.

* PRs welcome for:
  * Additional lightweight templates,
  * Better folder overviews using Bases,
  * Further small quality-of-life improvements.

If you publish your own variation, link it in a PR and I'll add a "Community Variants" list.

---

### Credits & further reading

* Companion post: [*Complete Obsidian vault guide tour*](https://bryanhogan.com/blog/obsidian-vault)
* On smart notes / Zettelkasten, MOCs, and bottom-up knowledge building ([see the blog post](https://bryanhogan.com/blog/obsidian-zettelkasten)).

> P.S. If you find this helpful, let me know!
