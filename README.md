# 🎙️ VoiceOffice v4

> A fully voice-controlled office suite — create documents, spreadsheets, and presentations hands-free using natural speech commands.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Web Speech API](https://img.shields.io/badge/Web%20Speech%20API-4285F4?style=flat&logo=google-chrome&logoColor=white)
![No Backend](https://img.shields.io/badge/Backend-None%20Required-brightgreen?style=flat)

**Live Demo →** [keerthanadev-on.github.io/voice-driven-office-editor/mainv2.html](https://keerthanadev-on.github.io/voice-driven-office-editor/mainv2.html)

---

## 📌 What is VoiceOffice?

VoiceOffice is a browser-based productivity suite that lets you create and edit Word documents, Excel spreadsheets, and PowerPoint presentations entirely through voice commands — no keyboard required.

Built as a single-file HTML application with zero backend dependencies, it uses the **Web Speech API** for real-time speech recognition and supports 100+ voice commands in natural language.

---

## ✨ Key Features

### 🎤 Voice Control
- **100+ voice commands** — formatting, navigation, file management, export
- **Natural language mode** — understands loose phrases like "make it bold" or "save this"
- **Dictation mode** — speak freely to type; punctuation commands supported
- **Table navigation mode** — navigate, fill, and read tables entirely by voice
- **Voice feedback (TTS)** — spoken confirmation for every command

### 📄 Word Processor
- Rich text editing with full formatting toolbar (bold, italic, font, color, alignment)
- Headings, bullet lists, numbered lists, blockquotes, horizontal rules
- Table insertion and navigation by voice
- Find & Replace, word count, spellcheck
- Page layout controls (margins, columns, line spacing)

### 📊 Spreadsheet
- Full Excel-like grid with formula bar
- Voice commands for cell navigation (`"go to B3"`), data entry (`"set C2 to 500"`)
- Aggregate functions by voice: sum, average, count, max, min
- Export to `.xlsx` and `.csv`

### 📽️ Presentations
- Multi-slide editor with 5 layout types and 5 color themes
- Voice commands to add/delete/duplicate slides, set titles and content
- Export to `.pptx` using PptxGenJS

### 🔄 Document Conversion (All 6 paths)
| From | To | Command |
|------|-----|---------|
| Word | Presentation | `"convert to presentation"` |
| Word | Spreadsheet | `"convert to excel"` |
| PPT | Word | `"convert to word"` |
| PPT | Spreadsheet | `"convert to excel"` |
| Excel | Word | `"convert to word"` |
| Excel | Presentation | `"convert to presentation"` |

### 🤖 AI Features
- **AI Create** — generate full documents, presentations, or spreadsheets from a text prompt
- **AI Chatbot** — built-in assistant that answers questions about voice commands
- Smart slide content generation based on topic keywords (pitch decks, lesson plans, research, marketing)

### ♿ Accessibility
- Designed for visually impaired users
- ARIA live regions for screen reader support
- Keyboard shortcuts: `Alt+W` (where am I), `Alt+R` (read document), `Alt+D` (describe screen)
- Accessibility mode with enhanced announcements

---

## 🗂️ Templates

**Word:** Resume, Business Report, Invoice, Letter, Meeting Notes, Project Proposal, To-Do List, Contract

**Excel:** Monthly Budget, Task Tracker, Inventory Sheet

**PowerPoint:** Pitch Deck (8 slides), Portfolio, Lesson Plan, Marketing Plan, Research Report, Project Timeline

---

## 🚀 Getting Started

No installation. No server. Just open the file.

```bash
git clone https://github.com/Keerthanadev-on/voice-driven-office-editor.git
cd voice-driven-office-editor
# Open mainv2.html in Chrome or Edge
```

> ⚠️ Requires **Chrome or Edge** for Web Speech API support. Allow microphone access when prompted.

---

## 🎮 Voice Command Examples

```
"create spreadsheet"           → opens new Excel document
"write Introduction in bold"   → types bold text
"insert table 3 by 4"          → inserts a 3×4 table
"enter table"                  → activates voice table navigation
"set slide title to Overview"  → edits current slide title
"go to B5"                     → navigates to cell B5
"export word"                  → downloads .doc file
"dark mode"                    → switches to dark theme
"convert to presentation"      → converts Word doc to slides
"start dictating"              → enters free-speech dictation mode
```

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `F2` | Toggle microphone |
| `F3` | Enter table navigation mode |
| `F4` | Toggle dictation mode |
| `F11` | Fullscreen |
| `F12` | Settings |
| `Ctrl+S` | Save |
| `Ctrl+N` | New document |
| `Alt+W` | Where am I (accessibility) |
| `Alt+R` | Read document aloud |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Vanilla HTML/CSS/JS | Entire application — no frameworks |
| Web Speech API | Real-time voice recognition + TTS |
| SheetJS (xlsx.js) | Excel file generation and export |
| PptxGenJS | PowerPoint file generation |
| LocalStorage | Auto-save and document persistence |
| Google Fonts | UI typography (Sora, JetBrains Mono) |

---

## 📁 Project Structure

```
voice-driven-office-editor/
├── mainv1.html     # Version 1
└── mainv2.html     # Version 2 (latest — full feature set)
```

---

## 🎯 Why I Built This

Voice-driven interfaces are an underexplored area in productivity software. Most office tools assume keyboard and mouse input, creating barriers for users with motor disabilities or those in hands-free environments. VoiceOffice explores what a fully accessible, zero-backend office suite could look like — built entirely with browser-native APIs.

---

## 👩‍💻 Author

**Keerthana Gulivindala**
B.Tech CSE · Andhra University College of Engineering for Women

[![GitHub](https://img.shields.io/badge/GitHub-Keerthanadev--on-181717?style=flat&logo=github)](https://github.com/Keerthanadev-on)

---

## 📄 License

MIT License — free to use and modify.
