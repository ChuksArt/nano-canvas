# nano-canvas 🍌🎨

A real-time, infinite whiteboard (Figma-style) that lets you draw, drag, and **edit images with Google Gemini 2.5 Flash**—no server required to start.

**Live demo (client-side only)**  
https://nano-canvas.vercel.app

---

## ⚡️ Features

| Feature | Status |
|---------|--------|
| Infinite, zoomable & pannable canvas | ✅ |
| Draw shapes (rect, circle, text, free-hand brush) | ✅ |
| Drag, resize, delete, duplicate, lock, z-order | ✅ |
| **AI image editing** (background swap, style transfer, object replace) via Gemini | ✅ |
| Text-to-image generation directly on canvas | ✅ |
| Multi-turn editing (keep refining the same object) | ✅ |
| Export PNG / SVG / PDF | ✅ |
| Real-time multiplayer cursors & chat (WebSocket) | 🚧 |
| User accounts + save/load boards (Supabase) | 🚧 |

---

## 🚀 Quick Start (zero backend)

```bash
git clone https://github.com/&lt;you&gt;/nano-canvas.git
cd nano-canvas/app
npm i
npm run dev        # localhost:5173
