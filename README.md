# Local Clipboard Manager

A lightweight, feature-rich, and secure single-file web application designed to save, organize, search, and manage your text snippets locally. Built with vanilla HTML, CSS, and JavaScript—no frameworks, build steps, or external dependencies required.

![Clipboard Manager Preview](https://img.shields.io/badge/status-active-success.svg) ![License](https://img.shields.io/badge/license-MIT-blue.svg)

---

## Features

- **Local Persistence:** All your clips are stored securely in your browser's `localStorage`.
- **Custom Categories:** Group your snippets dynamically with user-defined category badges.
- **Smart Search & Filtering:** Instantly filter your history by keyword (title/content) or narrow results down by category.
- **Expandable Long Text:** Automatically truncates long blocks of text or multi-line snippets with a smooth "Show more / Show less" toggle.
- **Drag-and-Drop & Touch Reordering:** Easily rearrange your clip order using desktop drag-and-drop or touch handles in Manage mode.
- **Backup & Restore:** Export your entire clipboard history to a JSON file or import a backup with a single click.
- **Keyboard Shortcuts:** 
  - `Ctrl + S` / `Cmd + S`: Instantly save your current snippet.
  - `/`: Jump directly to the search bar.
  - `Escape`: Clear search, close modals, or exit manage mode.
- **Accessibility Ready:** Fully responsive design with modal focus-trapping.

---

## Getting Started

Since this project is contained within a single file (`index.html`), running it requires no installation or local server setup.

1. Download or clone this repository.
2. Open the `index.html` file in any modern web browser (Chrome, Firefox, Safari, Edge).

---

## Usage Guide

1. **Adding a Clip:** Type or paste your text into the text area. Optionally add a **Title** and a **Category** (e.g., `Work`, `Code`, `Personal`), then click the save icon or press `Ctrl + S`.
2. **Copying a Clip:** Click the copy icon next to any saved snippet to instantly copy its text back to your system clipboard.
3. **Managing Clips:** Click the **Manage** button in the header of the saved clips section to reveal deletion options and reordering drag handles.
4. **Filtering & Searching:** Use the search bar to locate specific snippets, or use the category dropdown menu to filter by custom tags.
5. **Backing up Data:** Use the **Export** and **Import** buttons located in the input toolbar to backup or restore your JSON data payload.

---

## License

This project is open-source and available under the [MIT License](LICENSE).
