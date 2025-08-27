# 🔶 Hexadoca DMS

<div align="center">
<h3>Document Management Reimagined Through Spatial Navigation</h3>
<br/>

```
     ⬡ ⬡ ⬡
   ⬡ ⬡ ⬡ ⬡
     ⬡ ⬡ ⬡
```

[![License](https://img.shields.io/badge/license-MIT-gray.svg?colorA=2D2A2E&colorB=6B7280&style=flat)](./LICENSE)
[![Docker](https://img.shields.io/badge/docker-ready-gray.svg?colorA=2D2A2E&colorB=3B82F6&style=flat)](./docker)
[![ADHD](https://img.shields.io/badge/ADHD-optimized-gray.svg?colorA=2D2A2E&colorB=22C55E&style=flat)](./docs/adhd)

</div>

---

## 🎯 Navigation is Spatial, Not Hierarchical

Traditional DMS: `Folder > Subfolder > Document`  
**Hexadoca**: `Everything visible, spatially organized, one click away`

<table>
<tr>
<td width="33%">

### 📥 **Inbox** 
`#22C55E`  
Drop everything here  
AI sorts automatically

</td>
<td width="33%">

### 📄 **Documents**
`#3B82F6`  
Browse visually  
Think spatially

</td>
<td width="33%">

### 🔍 **Search**
`#F97316`  
Natural language  
"That blue thing"

</td>
</tr>
<tr>
<td width="33%">

### 📌 **Tasks**
`#EF4444`  
What needs attention  
Urgency-based

</td>
<td width="33%">

### 🗄️ **Archive**
`#A855F7`  
Long-term storage  
Timeline organized

</td>
<td width="33%">

### ⚙️ **System**
`#6B7280`  
Settings & control  
ADHD mode toggle

</td>
</tr>
</table>

---

## 🚀 Quick Start

```bash
# Clone
git clone https://github.com/yourusername/hexadoca.git
cd hexadoca

# Run with Docker
docker build -t hexadoca .
docker run -p 80:80 -v ./data:/app/data hexadoca

# Open browser
http://localhost
```

---

## 💡 Core Features

- **🔶 Hexagonal Navigation** - Spatial memory over hierarchical folders
- **🤖 AI Auto-Categorization** - Claude API sorts everything automatically  
- **👁️ Visual First** - See documents, don't read lists
- **🎯 ADHD Mode** - Reduces interface to essentials when overwhelmed
- **📱 Touch Optimized** - Large targets, no tiny buttons
- **🔍 Vibe Search** - Find by feeling: "that important thing from last week"
- **📦 Single Container** - One Docker container, no microservice maze

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| Backend | FastAPI (Python 3.11) |
| Frontend | React + SVG Hexagons |
| Database | PostgreSQL |
| AI | Claude API |
| OCR | Tesseract 5 |
| Search | Full-text + Fuzzy |
| Deploy | Docker |

---

## 📦 Installation

<details>
<summary><b>Docker (Recommended)</b></summary>

```bash
docker run -d \
  --name hexadoca \
  -p 80:80 \
  -v hexadoca-data:/app/data \
  -e CLAUDE_API_KEY=your-key \
  hexadoca/hexadoca:latest
```

</details>

<details>
<summary><b>Manual Installation</b></summary>

```bash
# Backend
cd backend
pip install -r requirements.txt
uvicorn main:app --host 0.0.0.0 --port 8000

# Frontend  
cd frontend
npm install
npm run build

# Start
docker-compose up
```

</details>

---

## 🧠 Why Hexagonal?

Research shows ADHD brains excel at spatial navigation over hierarchical organization. Hexagons provide:

- **Equal Distance** - Every option is one click away
- **Visual Memory** - Position becomes memory anchor
- **No Hierarchy** - No folder depths to forget
- **Color Coding** - Instant visual context

---

## 🔐 Privacy First

- 🏠 **Self-Hosted** - Your data stays on your server
- 🔒 **Encrypted Storage** - Optional at-rest encryption
- 🇪🇺 **GDPR Ready** - Full compliance built-in
- 📴 **No Telemetry** - Zero phone-home

---

## 📖 Documentation

- [Getting Started](./docs/getting-started.md)
- [ADHD Features](./docs/adhd-features.md)
- [API Reference](./docs/api.md)
- [Configuration](./docs/config.md)
- [Migration from Paperless](./docs/migration.md)

---

## 🤝 Contributing

Contributions welcome! Especially from neurodivergent developers who understand the struggle.

See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

---

## 📜 License

MIT License - See [LICENSE](./LICENSE) for details

---

<div align="center">
<br/>
<sub>Built with frustration at traditional DMS and love for ADHD minds</sub>
<br/>
<br/>

```
Made with ⬡ by the Hexadoca Team
```

</div>