# XTermux - Enhanced Termux Fork

![Build Status](https://github.com/CodeSpace-Xerox-1/XTermux/workflows/Build/badge.svg)
![Version](https://img.shields.io/badge/version-vAlpha.1-blue)

**XTermux** - Enhanced fork of [Termux](https://termux.dev) with extra features for power users.

## What's New in vAlpha.1

- ✅ Tkinter support (Python GUI)
- ✅ Enhanced color schemes
- ✅ Additional keyboard shortcuts
- ✅ Improved terminal emulation
- ✅ Custom themes
- ✅ Extended clipboard support

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
