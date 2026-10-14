# macOS\'s BYOVM via LLM
![preview0](preview/preview.png)

## Tech Stack

| Technology | Purpose |
|---|---|
| React 19 | UI framework |
| Vite 7 | Build tool & dev server |
| Tailwind CSS 4 | Styling |
| Framer Motion | Animations |
| GSAP | Advanced animations |
| Radix UI | Accessible UI primitives |
| React RND | Draggable/resizable windows |
| React Spring | Spring-based animations |
| Lucide React | Icons |

---

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
git clone https://github.com/recovery4184/Kexts_tahoe.git
cd Kexts_tahoe
npm install
```

### Development

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

--- 

### Want to Contribute?

Contributions are welcome! 🚀

1. Fork the repository  
2. Create your feature branch

```bash
git checkout -b feature/your-feature-name
```

3. Commit your changes

```bash
git commit -m "Add: your feature"
```

4. Push to the branch

```bash
git push origin feature/your-feature-name
```

5. Open a Pull Request



## Project Structure

```
src/
├── App.jsx               # Root component, boot/lock/desktop stage manager
├── app/                  # Individual macOS apps
│   ├── Finder.jsx        # File manager
│   ├── Safari.jsx        # Web browser
│   ├── Terminal.jsx      # Terminal emulator
│   ├── Spotify.jsx       # Music player
│   ├── Gallary.jsx       # Photo gallery
│   ├── Settings.jsx      # System settings
│   ├── Trash.jsx         # Trash bin
│   └── Blogs/
│       └── BlogsSection.jsx  # Notes app

├── components/           # Shared UI components
│   ├── AppWindow.jsx     # Draggable/resizable window shell
│   ├── Dock.jsx          # macOS dock
│   ├── TopBar.jsx        # Menu bar
│   └── ContextMenu.jsx   # Right-click menu
├── layouts/
│   ├── DesktopWindow.jsx # Desktop environment
│   ├── LockScreen.jsx    # Lock screen
│   └── PowerScreen.jsx   # Boot/power screen
└── store/
    └── Appstore.js       # Window management store
```

---

## License

MIT, GPLv2,3
