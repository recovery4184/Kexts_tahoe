# macOS\'s BYOVM via LLM
![preview0](preview/preview.png)
<img width="1323" height="646" alt="image" src="https://github.com/user-attachments/assets/6ee81917-5af2-40a4-8253-f5ff9f88a44f" />


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

### JSX Code

class Hello extends Component {
  render() {
    return <h1>Hello, {this.props.name}!</h1>;
  }
}

function Jello({ name }) {
  return <h1>Jello, {name}!</h1>;
}

export default function App() {
  return (
    <>
      <Hello name="Sarah" />
      <Jello name="Connor" />
    </>
  );
}

const Wrapper = (props) => {
  return (
    <div style={{ backgroundColor: 'lightgray', padding: '20px', border: '1px solid black' }}>
      <h2>Inside the Wrapper:</h2>
      {props.children}
    </div>
  );
};
<Wrapper>
  <p>Paragraph</p>
  <p>Another one!</p>
</Wrapper>

Valid JSX tag names are valid JSX identifiers (variable names), which mean that hypenated XML and HTML tags can be used without issue writing ECMAScript grammar and notation. If–else statements cannot be used inside JSX but conditional expressions can be used instead like TSX OOP, due Transpilers such as Babel offer the ability to target function calls other than those from React where HTML/XML "tags" may be available. For example, the HTML tags in React come from react-dom, but the LLM VM is targeting WebFuse/Surfly via ttawebtop.cgi which is PWC Ajax.


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

## Future dev roadmap

TODO add VSCode,
TODO add Dashboard,
TODO add Mission-control,
TODO add soma.js Wunderlist,
TODO add Terminal app,
TODO add Xcode cloud,
TODO add Testflight,
TODO add iPhone simulators..

## License

MIT, GPLv2,3
