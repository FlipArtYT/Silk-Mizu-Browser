# 🌊 Silk Mizu Browser
[![Lint](https://github.com/Silk-Project/Silk-Mizu-Browser/actions/workflows/main.yml/badge.svg)](https://github.com/Silk-Project/Silk-Mizu-Browser/actions/workflows/main.yml)
![Static Badge](https://img.shields.io/badge/License-MIT-blue)
![Commit Activity](https://img.shields.io/github/commit-activity/m/Silk-Project/Silk-Mizu-Browser)
<br>
Simple and lightweight PyQT6 browser for Silk and Linux / Windows / Mac computers. Made possible through the QWebEngineView Widget for rendering webpages. Mizu (水) translates to "water" in japanese, which makes sense because you are "surfing" the web.

![Browser Preview](/assets/preview.png)
![AI Sidebar Preview](/assets/preview_ai.png)

## ⭐️ Features
- Simple but still modern UI elements using the Awesome 6 icons and QT Dark theme
- Default search engine selection (Google, DuckDuckGo, Brave...)
- Custom start page selection
- Basic browser navigation features (e.g. going back a page)
- Accessability features (zooming, font size)
- Bookmarks and easy Bookmark management
- Silk-Start support
- Easy to use Tab system
- AI webpage summarization (optional and local, without data collection)
- Download Manager

## ⚙️ Requirements
- `pyqt6` (pip)
- `pyqt6-webengine` (pip)
- `qtawesome` (pip)
- `pyqtdarktheme` (pip)
- `darkdetect` (pip)
- `ollama` (pip and system wide)

## ⬇️ Getting the program
A normal git clone will result into missing submodules. Instead use this command:
```
git clone --recursive https://github.com/Silk-Project/Silk-Mizu-Browser.git
```
...or initialize the submodules later:
```
git submodule update --init --recursive
```


## 🚀 Running the program
To use this program, simply execute the main.py file directly via python3.
```
python3 main.py
```
## 💻 To-do
- [ ] Improve website tab system and tab bar positioning at the top
- [x] "Explain selected text with AI" (partly)
- [ ] Reader view
- [ ] Better overview of current downloads so it can't infinitely stack up in the download menu
- [x] Multi-language support
- [ ] Custom extension store (for the browser itself)
- [ ] Widgets (e. g. Notes and additional widgets from the store)
- [ ] Custom theme editor (with theme import)

## 👥 Contributing
Feel free to open issues and create pull requests.
