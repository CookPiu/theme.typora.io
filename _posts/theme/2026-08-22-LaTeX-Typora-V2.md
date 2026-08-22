---
layout: theme
title: LaTeX Typora V2
category: theme
homepage: https://github.com/shamsghi/LatexTypora
download: https://github.com/shamsghi/LatexTypora/releases/latest
built-in: false
author: shamsghi
thumbnail: latex-typora-v2.png
typora-root-url: ../../
typora-copy-images-to: ../../media/theme/latex-typora
---

# LaTeX Typora V2

LaTeX Typora V2 gives long-form Markdown and technical documentation the typography and spacing of a LaTeX document. The family includes light and dark reading themes plus a developer-dark variant.

<div style="display: flex; gap: 16px; flex-wrap: wrap; align-items: flex-start;">
  <div style="flex: 1 1 280px; text-align: center;">
    <img src="/media/theme/latex-typora/v2-light.png" alt="LaTeX Typora V2 light mode" style="width: 100%;">
    <p>Light mode with New Computer Modern</p>
  </div>
  <div style="flex: 1 1 280px; text-align: center;">
    <img src="/media/theme/latex-typora/v2-dark.png" alt="LaTeX Typora V2 dark mode" style="width: 100%;">
    <p>Dark mode with the same document geometry</p>
  </div>
</div>

## Made to read like a paper

The light and dark themes set body text in New Computer Modern. Their 32em measure, 1.55em paragraph indent, zero paragraph spacing, numbered sections, LaTeX list markers, `booktabs` tables, and footnotes follow `article.cls` metrics at 11pt on letter paper.

![Attention Is All You Need rendered in LaTeX Typora](/media/theme/latex-typora/v2-paper.png)

<p align="center"><em>Attention Is All You Need</em> rendered inside Typora</p>

## What is new in V2

- **New Computer Modern throughout:** V2 bundles local serif, sans, and mono families for prose, labels, and code.
- **LaTeX document geometry:** The reading measure, paragraph rhythm, headings, lists, tables, quotations, and footnotes use LaTeX conventions.
- **HTML exports keep the typeface:** Embedded WOFF2 subsets preserve New Computer Modern on machines without the theme installed.
- **Three variants:** `latex.css` and `latex-dark.css` focus on reading. `latex-dev-dark.css` covers READMEs, API notes, specifications, and changelogs.
- **Multilingual text:** V2 includes Noto Nastaliq for Urdu and Persian plus cross-platform CJK font stacks.
- **No network dependency:** The themes load their fonts without a CDN or network connection.

## A developer variant that behaves like documentation

The developer theme uses a 46em monospace measure with left-aligned text. Fenced blocks keep their language labels in reading mode and exports; diff rows carry full-width add and remove tints. Wide code, tables, and diagrams show their scrollbars.

![LaTeX Typora developer dark variant](/media/theme/latex-typora/v2-developer.png)

<p align="center">The developer-dark variant for code-heavy Markdown</p>

## Installation

### Automatic

macOS and Linux:

```bash
curl -fsSL https://raw.githubusercontent.com/shamsghi/LatexTypora/main/scripts/install.sh | bash
```

Windows PowerShell:

```powershell
irm https://raw.githubusercontent.com/shamsghi/LatexTypora/main/scripts/install-windows.ps1 | iex
```

### Manual

1. Download and unzip the [latest release](https://github.com/shamsghi/LatexTypora/releases/latest).
2. In Typora, open **Preferences → Appearance → Open Theme Folder**.
3. Copy `latex.css`, `latex-dark.css`, `latex-dev-dark.css`, and `latex_fonts/` into that folder.
4. Restart Typora and choose a LaTeX theme from the **Themes** menu.

For source, customization, demos, and release notes, visit [shamsghi/LatexTypora](https://github.com/shamsghi/LatexTypora).
