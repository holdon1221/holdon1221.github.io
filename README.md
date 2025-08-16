# 🎓 ScholarSite CLI

[![GitHub stars](https://img.shields.io/github/stars/holdon1221/ScholarSite?style=social)](https://github.com/holdon1221/ScholarSite/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/holdon1221/ScholarSite?style=social)](https://github.com/holdon1221/ScholarSite/network/members)
[![Sponsor](https://img.shields.io/badge/Sponsor-❤️-red?style=flat&logo=github)](https://github.com/sponsors/holdon1221)

Professional academic homepage builder with AI-powered features.

## 📖 Demo

**[🌐 View Live Demo](https://holdon1221.github.io/ScholarSite/)**

See what your academic homepage will look like!

## 🚀 Quick Start

**Fork first** for easy GitHub Pages deployment:

1. **Fork this repository** on GitHub 
2. **Rename your fork** to `YOUR-USERNAME.github.io` (replace with your GitHub username)
3. **Clone and setup**:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
cd YOUR-USERNAME.github.io
npm install
npm start  # One command: setup → build → serve
```

Your site will be live at: `https://YOUR-USERNAME.github.io/`

⚠️ **Windows users**: Run terminal as Administrator if you encounter permission errors.
⚠️ **Python deps**: Auto-installs PyMuPDF, Pillow, Tesseract. Activate your virtual environment before `npm install` if using one.

## ✨ What Happens

1. **Environment Check**: Verifies Node.js ≥18.0.0
2. **Auto-Install**: Downloads and installs all dependencies
3. **Interactive Setup**: Guides you through configuration
4. **PDF Processing**: Extracts and enhances your publications
5. **Homepage Generation**: Creates your professional website
6. **Local Server**: Serves at `http://localhost:8000`

## 📋 Commands

```bash
scholarsite start           # Complete setup → build → serve
scholarsite setup           # Interactive configuration
scholarsite build           # Generate homepage
scholarsite serve           # Start local server
scholarsite translate       # AI-powered translation
scholarsite doctor          # Diagnose issues
```

## 🔧 Requirements

- **Node.js ≥18.0.0** (automatically checked)
- **npm** (comes with Node.js)
- **Internet connection** (for dependency installation)

## 🏗️ What Gets Built

- `index.html` - Your academic homepage
- `style.css` - Professional styling
- `data/publications.json` - Publication data
- Local server on `http://localhost:8000`

## 🙏 Acknowledgments

- **Citation Crawler**: Inspired by [RayeRen/rayeren.github.io](https://github.com/RayeRen/rayeren.github.io)
- **Development**: Built with assistance from [Claude Code](https://claude.ai/code)

## 📄 License

MIT License - See [LICENSE](LICENSE) file for details.

---

**Get started in minutes**: Fork → Rename to `username.github.io` → Clone → Install → Deploy!