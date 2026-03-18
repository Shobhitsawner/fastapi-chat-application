# ⚡ VelocityChat: Real-Time WebSocket Engine
**A high-concurrency, asynchronous chat application built with FastAPI and modern WebSocket protocols.**

[![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)](https://fastapi.tiangolo.com/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![WebSockets](https://img.shields.io/badge/WebSockets-Socket.io-lightgrey?style=for-the-badge&logo=socketdotio)](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API)

---

## 🌟 Overview
VelocityChat is a lightweight yet powerful demonstration of **bi-directional, real-time communication**. By leveraging FastAPI's native support for WebSockets and Python's `asyncio`, this app handles multiple concurrent connections with minimal overhead. It’s a perfect example of how to build low-latency communication systems without heavy external libraries.

### ✨ Key Features
* **⚡ Instant Messaging:** Zero-latency communication via persistent WebSocket connections.
* **🧠 Async Core:** Fully non-blocking backend architecture for high-performance scaling.
* **🎨 Modern UI:** A clean, responsive "Vanilla" frontend (HTML/CSS/JS) designed for speed.
* **🛠 Structured Architecture:** Separation of static assets, Jinja2 templates, and core API logic.
* **📡 Broadcast Logic:** Efficient message distribution to all active client instances.

---

## 🛠️ Tech Stack
| Component | Technology |
| :--- | :--- |
| **Backend** | Python 3.10+, FastAPI |
| **Server** | Uvicorn (ASGI) |
| **Frontend** | Vanilla JavaScript, HTML5, CSS3 |
| **Templating** | Jinja2 |
| **Protocol** | WebSockets (ws://) |

---

## 📂 Project Anatomy
```text
chatAPP/
├── static/              # Assets
│   ├── css/style.css    # Minimalist Chat Styling
│   └── js/script.js     # WebSocket Client Logic
├── templates/           # Server-side Rendered Views
│   └── index.html       # Main Chat Interface
├── main.py              # WebSocket Routes & Event Handlers
└── requirements.txt     # Dependency Manifest
