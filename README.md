# HasTok Split View

A lightweight split-view prototype that pairs a Figma prototype with a Microsoft Form side by side. Built as a single static HTML file with no dependencies.

## What It Does

- **Left pane:** Embedded Figma prototype for interactive walkthrough
- **Right pane:** Embedded Microsoft Form for collecting feedback
- **Draggable divider** to resize panes — double-click to reset to 50/50
- **Responsive layout** — stacks vertically on screens under 900px
- **Keyboard accessible** — arrow keys to resize, Enter to reset

## Usage

Open `index.html` in a browser, or visit the hosted version on GitHub Pages.

To swap in a different Figma prototype or form, edit the `src` attributes on the two `<iframe>` elements in `index.html`.

## Hosting

This is a static single-file site. It's hosted via GitHub Pages — no build step or server required.
