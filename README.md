


# WormGPT-
🔥 The WormGPT Ollama UI is complete with:   • All 70+ features implemented  • 3 revolutionary features (Context Visualizer, Multi-Model Consensus, Timeline Replay)  • Permanent unremovable watermark crediting MRZXN with mrzxnportal.netlify.app  • Professional ChatGPT-style design maintained


join us for more project!

https://t.me/ventalgroup

or check my website https://mrzxnportal.netlify.app/

# 🐛 WormGPT Enhanced

A professional AI chat interface with 20+ advanced features, powered by local Ollama LLMs.

## ⚡ Quick Start (One Command)

```bash
chmod +x install.sh && ./install.sh
```

Then:
```bash
./start.sh
```

Open: **http://localhost:3001**  
Password: **Realnojokepplwazy1234**

---

## 📋 Prerequisites
- Node.js 18+
- Ollama (auto-installed by install.sh)
- macOS / Linux / WSL

---

## 🔧 Manual Setup

```bash
# 1. Install Ollama
curl -fsSL https://ollama.ai/install.sh | sh

# 2. Pull model (required)
ollama pull godmoded/llama3-lexi-uncensored

# 3. Start Ollama
ollama serve

# 4. Install deps
cd app && npm install && npm run build && cd ..
cd server && npm install && cd ..

# 5. Start server
cd server && node index.js
```

---

## 🚀 Features

| # | Feature | Description |
|---|---------|-------------|
| 1 | **Terminal Runner** | Real shell execution via WebSocket |
| 2 | **Live HTML Preview** | Sandboxed iframe preview |
| 3 | **Website Builder** | Drag-drop block builder + export |
| 4 | **Artifact Panel** | Side-panel code viewer with preview |
| 5 | **VS Code / Cursor** | One-click open in editor |
| 6 | **Diff Viewer** | Inline before/after code diff |
| 7 | **Project Editor** | Upload ZIP → multi-file editor |
| 8 | **Auto-Summarization** | Unlimited context via memory layers |
| 9 | **Knowledge Base** | Upload docs → RAG search |
| 10 | **Mind Map Canvas** | Interactive drag-drop planning board |
| 11 | **Code Block Runner** | Run Python/JS/Bash directly in chat |
| 12 | **Auto Debug** | Error detection in terminal |
| 13 | **Shell Executor** | Terminal passthrough |
| 14 | **Mermaid Diagrams** | Live diagram renderer & editor |
| 15 | **Git Integration** | Status, diff, commit, branch from UI |
| 16 | **4 Parallel Variants** | Generate 4 responses side-by-side |
| 17 | **Command Palette** | Ctrl+K quick command launcher |
| 18 | **Copy-as** | Export as cURL / Python / JSON / MD |
| 19 | **Collaboration** | Share link (Pro feature preview) |
| 20 | **Session Resume** | Auto-save + restore last session |

---

## ⌨️ Keyboard Shortcuts

- `Ctrl+K` / `Cmd+K` — Command Palette
- `Enter` — Send message
- `Shift+Enter` — New line
- `ESC` — Close modals
- `↑/↓` — Terminal history

---

## 🔌 Architecture

```
wormgpt/
├── app/          # React + Vite frontend
│   └── src/App.tsx   # All UI (single file)
├── server/       # Express + WebSocket backend
│   └── index.js  # API + terminal proxy
├── install.sh    # One-command setup
├── start.sh      # Production start
└── dev.sh        # Development (hot-reload)
```

---

**Created by MRZXN** — All rights reserved.
