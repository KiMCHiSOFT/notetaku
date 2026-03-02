<div align="center">
  <img src="notetaku-logo.png" alt="notetaku" width="128" />
  <h1>notetaku</h1>
  <p><strong>organize your life with notes, without the bloat</strong></p>
  <p>a fast, private, offline-first note-taking app built with Tauri</p>
</div>

---

## features

- **markdown editor** - full markdown support with live preview, toolbar, and keyboard shortcuts
- **session capture** - start a work session and log entries as you go, timestamped and organized
- **notebooks** - organize notes into color-coded notebooks
- **wiki-links** - link notes together with `[[wiki-links]]` and view backlinks
- **full-text search** - instant search across all notes powered by SQLite FTS5
- **tags** - tag notes and filter by tag
- **calendar view** - browse notes by date
- **templates** - create reusable note templates
- **sticky notes** - pop out notes as floating sticky windows
- **attachments** - attach files to notes with drag-and-drop
- **vault encryption** - encrypt your workspace with AES-256-GCM + Argon2id
- **real-time collaboration** - peer-to-peer note sharing over local network
- **export** - export notes as markdown or HTML
- **themes** - light, dark, and custom accent colors
- **auto-updates** - in-app update checking with one-click install

## install

### windows

1. download the latest `.exe` installer from [releases](https://github.com/KiMCHiSOFT/notetaku/releases)
2. run the installer (installs to current user, no admin required)
3. launch notetaku from the start menu

### building from source

notetaku is closed source. prebuilt installers are available on the [releases](https://github.com/KiMCHiSOFT/notetaku/releases) page.

## usage

1. **create a workspace** - on first launch, a default workspace is created automatically
2. **write notes** - click the + button or press `Ctrl+N` to create a new note
3. **organize** - create notebooks, add tags, and use wiki-links to connect ideas
4. **sessions** - press `Ctrl+Shift+S` to start a work session and capture timestamped entries
5. **search** - press `Ctrl+K` to open the command palette, or use the search view
6. **sticky notes** - right-click a note and select "sticky" to pop it out as a floating window

## keyboard shortcuts

| shortcut | action |
|----------|--------|
| `Ctrl+N` | new note |
| `Ctrl+K` | command palette |
| `Ctrl+Shift+S` | start/stop session |
| `Ctrl+Shift+P` | join shared note |

## data & privacy

all data is stored locally on your machine. notetaku makes zero network calls except for optional update checking (which only contacts GitHub). your notes never leave your computer.

data is stored at:
- **windows**: `%APPDATA%/notetaku/workspaces/`
- **linux/macos**: `~/.notetaku/workspaces/`

## roadmap

### in progress
- [ ] onboarding - guided task-based tutorial that teaches features by doing, earn a "pro" badge
- [ ] linux and macos builds

### planned
- [ ] note version history
- [ ] kanban board view
- [ ] pdf export
- [ ] workspace backup and restore
- [ ] mobile companion app (android/ios)
- [ ] plugin system

### recently shipped
- [x] inline font size controls (v0.4.1)
- [x] right-click context menu with delete, archive, share (v0.4.1)
- [x] note pinning, sorting, templates, duplicate, word count (v0.4.0)
- [x] in-app auto-updates (v0.4.0)
- [x] vault encryption with AES-256-GCM (v0.3.0)
- [x] session capture (v0.2.0)
- [x] wiki-links and backlinks (v0.2.0)
- [x] notebooks with color coding (v0.2.0)
- [x] full-text search (v0.1.0)
- [x] sticky notes (v0.3.0)
- [x] peer-to-peer note sharing (v0.3.0)

## support

notetaku is free to use. if you find it useful, consider supporting development:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/kimchisoft)

## license

proprietary freeware - see [LICENSE](LICENSE) for details. free to use for any purpose. redistribution and modification for distribution are not permitted.

copyright 2025 KiMCHiSOFT
