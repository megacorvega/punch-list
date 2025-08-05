# 👊 Punch List

A fast, keyboard-first checklist app for organizing and tracking nested tasks with Markdown-inspired shortcuts.

## ✨ Features

- ✅ Keyboard-driven task management
- 🧱 Support for indentation, project headers, notes, and labels
- 🎨 Custom highlight styles (In Progress, Follow Up, Hold, etc.)
- 💾 Auto-saves to local browser storage
- 📁 JSON import/export for backup and sharing
- 🧭 Sidebar for list navigation
- 📎 floating key legend with shortcuts
- 💻 Works offline, no login or backend required

## 🔤 Supported Syntax

You can type directly into the editor using:

- `# Title` – Project Header
- `## Section` – Subsection Header
- `- Task` – Checkbox Task
- `> Note` – Italicized note block
- `Ctrl/Cmd + Alt + [1–4]` – Apply color highlights

## ⌨️ Keyboard Shortcuts

| Action                | Shortcut                    |
|-----------------------|-----------------------------|
| New Line              | `Enter`                     |
| Indent / Unindent     | `Tab` / `Shift + Tab`       |
| Check / Uncheck       | `Shift + Enter`             |
| Move Task Up/Down     | `Shift + ↑ / ↓`             |
| Move Project Up/Down  | `Ctrl + Alt + Shift + ↑ / ↓`|
| Break Out of Project  | `Ctrl + Enter`              |
| Create/Delete List    | `Ctrl + Alt + N / D`        |
| Switch List           | `Ctrl + Alt + W / S`        |
| Apply Highlight       | `Ctrl + Alt + [1–4]`        |

## 📦 Development

Clone the repo and open the `index.html` file in your browser.

```bash
git clone https://github.com/yourusername/punch-list.git
cd punch-list
open index.html
```

> 💡 No build step required — it’s just HTML, CSS, and JS.

## 📁 Folder Structure

```
/punch-list
│
├── index.html
├── /src
│   ├── /css
│   │   ├── style.css
│   │   └── themes.css
│   └── /js
│       └── app.js
```

## 🔒 Privacy & Storage

All data is saved locally in your browser using `localStorage`. No tracking, no cloud, no nonsense.

## 📜 License

MIT — use it, fork it, make it your own.

## Future Updates Planned
- Dockerized & Self Hosted. Will stay as a dumb html interface for the time being
