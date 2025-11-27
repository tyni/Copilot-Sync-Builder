# 🧠 Copilot Sync Builder

**Copilot Sync Builder** is a tool that helps you extract, curate, and generate structured sync files from your saved Copilot chat history. Whether you're organizing a massive archive or just want to keep the best insights, this tool gives you full control over what to keep, edit, group, and export — all through a visual tree interface.

---

## ✨ Features

- ✅ Parse saved Copilot conversations (`outerHTML`)
- 🗂️ View Q&A in a collapsible tree (Original or Semantic Grouping)
- 🔁 Detect presumed repeats and follow-up threads
- ✅ Checkbox, edit, tag, and merge Q&A
- 🧠 Generate Sync Files to preserve memory state
- 📤 Export selected Q&A as chunk files for reuse or replay

---

## 🚀 How to Use

### 1. Save Your Chat
Export your Copilot conversation as `copilot_conversation.html` (right-click → Save As → Webpage, Complete).

### 2. Parse the HTML
Run the parser to extract Q&A pairs:

```bash
python generate_tree_data.py
