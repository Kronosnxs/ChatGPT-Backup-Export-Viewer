# ChatGPT Backup Export Viewer

<img width="1024" height="1024" alt="banner" src="https://github.com/user-attachments/assets/53374f85-6fa2-403f-bc22-5346539c7769" />

A **stand-alone HTML + JavaScript tool** to explore, search, and restore your official ChatGPT data exports — including messages, attachments, and metadata — all **offline** and directly in your browser.

No setup. No dependencies. No server.

---

## 🚀 Overview

The **ChatGPT Backup Export Viewer** allows you to open your ChatGPT data export (`conversation.json`, `chat.html`, and the `user-...` attachment folder) and navigate your entire history with full-text search, attachment mapping, and export options.

It’s designed for creators, researchers, and developers who want to **recover**, **index**, or **archive** their ChatGPT data securely.

---

## ✨ Key Features

| Feature | Description |
|----------|-------------|
| 🧠 **Multi-source merge** | Combines messages from both `conversation.json` and `chat.html` automatically. |
| 📎 **Attachment linking** | Detects and previews all exported files (`file_…`) across root and `user-…` subfolders. |
| 🔍 **Full-text search** | Search any word or phrase across all messages and attachments. Highlights and scrolls to hits instantly. |
| 💾 **Export tools** | Export conversations as `JSON`, `Markdown`, or a `Restore Manifest` text file. |
| 🧰 **Offline & secure** | 100 % local processing — no data ever leaves your device. |
| ⚙️ **Drag & drop support** | Drop your files or folders anywhere on the page to load them. |
| 🧷 **Safety first** | All message HTML/JS is escaped before rendering; nothing is executed. |

---

## 🧩 How to Use

1. **Open** `chatgpt_backup_export_viewer.html` in your browser.  
2. **Load** your `conversation.json` and `chat.html` files.  
3. **Import** the folder with your exported attachments (`user-xxxx`).  
4. **Search** through all messages or browse via the sidebar.  
5. **Export** selected conversations to Markdown or JSON, or create a **Restore Manifest** for archiving.

Everything runs entirely in your browser — no installation or internet connection needed.

---

## 🗂 Example Folder Layout

```
ChatGPT_Export/
├── conversation.json
├── chat.html
├── file_00000001.png
└── user-bftZnENzsjQsrzG0eum96Wo9/
    ├── file_00000002.json
    └── file_00000003.png
```


---

## 🧱 Technical Details

- Built with **Vanilla JavaScript**, **HTML5**, and **CSS3**
- Uses native browser APIs:
  - `FileReader`, `DOMParser`, `Blob`, and `URL.createObjectURL`
- Works on all modern browsers (Chrome, Firefox, Edge, Safari)

---

## 🧩 Export Types

| Type | Output | Description |
|------|---------|-------------|
| **JSON** | `conversation.json` | Structured data of messages and attachments. |
| **Markdown** | `conversation.md` | Readable export for documentation or archiving. |
| **Restore Manifest** | `.txt` | Human-readable reference for folder reconstruction. |

---

## 🛠 Future Ideas

- Boolean / regex search (AND / OR / wildcards)  
- Syntax highlighting for code blocks  
- Date range filtering  
- Multi-conversation ZIP export  
- Advanced preview support (PDF, video, audio)

---

## 📦 Metadata

**Project name:** ChatGPT Backup Export Viewer  
**Version:** 0.9.4  
**Author:** [Kronosnxs (Bob)](https://github.com/kronosnxs)  
**License:** MIT  
**MD5:** `114dc4609dd468e46c35998f1a89f64a`  
**File size:** 59 KB  

---

> 🧩 “Your AI memories deserve a proper archive.”  
> — *ChatGPT Backup Export Viewer*
