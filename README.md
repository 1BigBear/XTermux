# XTermux - Enhanced Termux Fork

![Build Status](https://github.com/CodeSpace-Xerox-1/XTermux/workflows/Build/badge.svg)
![Version](https://img.shields.io/badge/version-vAlpha.2-blue)

**XTermux** - Enhanced fork of [Termux](https://termux.dev) with extra features for power users.

## What's New in vAlpha.2

- ✅ Tkinter support (Python GUI)
- ✅ PySide6 support (Python Qt GUI)
- ✅ Swing support (Java GUI)
- ✅ PyQt support
- ✅ All GUI modules for all languages
- ✅ Built-in GUI app launcher (like PyDroid 3)
- ✅ Enhanced color schemes
- ✅ Additional keyboard shortcuts
- ✅ Improved terminal emulation
- ✅ Custom themes
- ✅ Extended clipboard support
- ✅ 32-bit (armv7a) and Universal APK builds

## Installation

Download the latest APK from [Releases](https://github.com/CodeSpace-Xerox-1/XTermux/releases)

## Features

### Tkinter Support
Run Python GUI applications directly in terminal:
```bash
pkg install python
pip install tkinter
python your_gui_app.py
```

### Enhanced Terminal
- Better Unicode support
- Improved scrollback
- Custom cursor styles
- Screen recording support

## Differences from Termux

| Feature | Termux | XTermux |
|---------|--------|---------|
| Tkinter | ❌ | ✅ |
| Themes | Basic | Extended |
| Shortcuts | Limited | Enhanced |

## Building

```bash
git clone https://github.com/CodeSpace-Xerox-1/XTermux.git
cd XTermux
./gradlew assembleDebug
```

## Credits

Based on [Termux](https://github.com/termux/termux-app) by Fredrik Fornwall and contributors.

## License

Same as Termux - See LICENSE.md
