# 📄 PDF Viewer

> A modern, high-performance web-based PDF viewer with advanced folder management and intelligent text/image handling.

[![Live Demo](https://img.shields.io/badge/🚀-Live%20Demo-blue?style=for-the-badge)](https://yourusername.github.io/pdf-viewer)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![PDF.js](https://img.shields.io/badge/PDF.js-v3.11.174-red?style=for-the-badge)](https://mozilla.github.io/pdf.js/)

## ✨ Features

### Core Functionality
- **📁 Folder-based PDF Management** - Select entire folders containing PDF files for streamlined workflow
- **🖼️ Dynamic Thumbnail Navigation** - Auto-generated page thumbnails with real-time navigation
- **⚡ High-Performance Rendering** - 3x quality rendering with optimized viewport management
- **📱 Responsive Design** - Seamless experience across desktop, tablet, and mobile devices

### Advanced Capabilities
- **✂️ Precision Area Capture** - Select and copy any region to clipboard with pixel-perfect accuracy
- **🧠 Smart Copy System** - Intelligent text/image detection with automatic clipboard optimization
- **⌨️ Comprehensive Keyboard Support** - Full keyboard navigation and shortcuts for power users
- **🔍 Adaptive Zoom Controls** - Mouse-centered zooming with fit-to-width/page modes
- **📄 Seamless Text Selection** - Native PDF text selection with proper Unicode handling

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)
1. Visit the [live demo](https://yourusername.github.io/pdf-viewer)
2. Select your PDF folder or drag files directly

### Option 2: Local Development
```bash
git clone https://github.com/yourusername/pdf-viewer.git
cd pdf-viewer
# Serve with any static server (e.g., Python, Node.js, or VS Code Live Server)
python -m http.server 8000
# Open http://localhost:8000
```

## 🎮 Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl + B` | Toggle sidebar |
| `Ctrl + Shift + X` | Area capture mode |
| `Ctrl + C` | Smart copy (text/image) |
| `Ctrl + A` | Select all text |
| `Ctrl + Wheel` | Mouse-centered zoom |
| `Ctrl + +/-` | Zoom in/out |
| `Arrow Keys` | Navigate pages |
| `ESC` | Exit capture mode / Close sidebar |

## 🛠️ Technical Stack

- **Frontend**: Vanilla JavaScript (ES6+), HTML5, CSS3
- **PDF Engine**: [PDF.js v3.11.174](https://mozilla.github.io/pdf.js/) by Mozilla
- **Rendering**: HTML5 Canvas with high-DPI optimization
- **Architecture**: Modular class-based design with event-driven state management

## 📐 Architecture Overview

```
PDFClipboard Class
├── Rendering Engine
│   ├── High-quality canvas rendering (3x scale)
│   ├── Viewport optimization
│   └── Text layer overlay
├── UI Management
│   ├── Responsive sidebar system
│   ├── Dynamic thumbnail generation
│   └── Adaptive toolbar controls
├── Input Handling
│   ├── File/folder selection
│   ├── Drag & drop support
│   └── Keyboard shortcuts
└── Clipboard Integration
    ├── Area capture system
    ├── Smart text/image detection
    └── High-quality image export
```

## 🔧 Browser Compatibility

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 90+ | ✅ Fully Supported |
| Firefox | 88+ | ✅ Fully Supported |
| Safari | 14+ | ✅ Fully Supported |
| Edge | 90+ | ✅ Fully Supported |

**Requirements:**
- Modern browser with ES6+ support
- File API and Clipboard API support
- HTML5 Canvas support

## 🎯 Performance Optimizations

- **Lazy Loading**: Thumbnails generated on-demand
- **Memory Management**: Efficient canvas recycling and cleanup
- **Render Optimization**: Debounced text layer updates during zoom operations
- **File Handling**: Streaming-based PDF parsing for large files
- **UI Responsiveness**: Hardware-accelerated CSS transitions

## 🔒 Security & Privacy

- **Client-Side Only**: All PDF processing happens in your browser
- **No Data Upload**: Files never leave your device
- **No Tracking**: Zero analytics or external service calls
- **Secure Origins**: HTTPS deployment for Clipboard API access

## 📱 Usage Examples

### Basic PDF Viewing
1. Click "폴더 선택" to select a folder containing PDFs
2. Use the folder explorer (📁) to navigate between files
3. View page thumbnails (🖼️) for quick navigation

### Advanced Features
- **Area Capture**: `Ctrl+Shift+X` → Drag to select → Auto-copy to clipboard
- **Smart Copy**: Select text then `Ctrl+C` for text, or `Ctrl+C` without selection for full page image
- **Power Navigation**: Use arrow keys for page navigation, `Ctrl+B` for sidebar toggle

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Bug Reports**: Use GitHub Issues with detailed reproduction steps
2. **Feature Requests**: Describe use cases and expected behavior
3. **Code Contributions**: Fork, create feature branch, submit PR
4. **Documentation**: Improve README, add examples, or create tutorials

### Development Setup
```bash
# Clone and setup
git clone https://github.com/yourusername/pdf-viewer.git
cd pdf-viewer

# No build process required - pure vanilla JS
# Just serve the files with any static server
```

## 📊 Project Stats

- **Bundle Size**: 0 KB (no bundling required)
- **Dependencies**: 1 (PDF.js CDN)
- **Lines of Code**: ~2000 (well-documented)
- **Load Time**: <2s on average connection

## 🎨 Customization

The viewer is designed for easy customization:

- **Themes**: Modify CSS variables for color schemes
- **Layout**: Responsive design adapts to container size
- **Features**: Modular class structure for easy feature addition/removal

## 📋 Roadmap

- [ ] **Multi-language Support** - i18n implementation
- [ ] **Advanced Search** - Full-text PDF search
- [ ] **Annotation Support** - Basic markup tools
- [ ] **Bookmarks** - Save and restore reading positions
- [ ] **Print Optimization** - Enhanced print layouts
- [ ] **PWA Support** - Offline capability

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Mozilla PDF.js](https://mozilla.github.io/pdf.js/) - Powerful PDF rendering engine
- [MDN Web Docs](https://developer.mozilla.org/) - Comprehensive web API documentation
- Open source community for inspiration and feedback

---

<div align="center">

**[Live Demo](https://yourusername.github.io/pdf-viewer)** • **[Report Bug](https://github.com/yourusername/pdf-viewer/issues)** • **[Request Feature](https://github.com/yourusername/pdf-viewer/issues)**

Made with ❤️ for better PDF reading experience

</div>
