# The Alchemist's Library - Desktop App

Beautiful book collection application now available as a downloadable desktop app for Windows, macOS, and Linux!

## 📥 Download

Head to the [Releases](https://github.com/dazzloc/alchemists-library/releases) page to download the app for your operating system:

- **Windows**: Download `.exe` installer or portable version
- **macOS**: Download `.dmg` installer
- **Linux**: Download `.AppImage` or `.deb` package

## 🚀 Installation

### Windows
1. Download `Alchemists-Library-Setup.exe`
2. Run the installer and follow the installation wizard
3. Launch from your Start Menu or Desktop shortcut

### macOS
1. Download `Alchemists-Library.dmg`
2. Open the file and drag the app to your Applications folder
3. Launch from Applications

### Linux
**Option 1: AppImage (Universal)**
1. Download `Alchemists-Library.AppImage`
2. Make it executable: `chmod +x Alchemists-Library.AppImage`
3. Run it: `./Alchemists-Library.AppImage`

**Option 2: Debian/Ubuntu**
1. Download `alchemists-library_1.0.0_amd64.deb`
2. Install: `sudo dpkg -i alchemists-library_1.0.0_amd64.deb`
3. Launch from your app menu

## 🛠️ Development

### Prerequisites
- Node.js 16+ 
- npm or yarn

### Setup
```bash
git clone https://github.com/dazzloc/alchemists-library.git
cd alchemists-library
npm install
```

### Run Development Version
```bash
npm start
```

### Build
```bash
# Build for current platform
npm run build

# Build for specific platform
npm run build:win    # Windows
npm run build:mac    # macOS
npm run build:linux  # Linux

# Build for all platforms
npm run build:all
```

## 📦 Release Process

To create a new release:

1. Commit your changes
2. Create a git tag:
   ```bash
   git tag v1.0.1
   git push origin v1.0.1
   ```
3. GitHub Actions will automatically build and upload the apps to Releases

## 🎨 Features

- 📚 Beautiful book collection management
- 🔍 Search functionality
- 📊 User dashboard with statistics
- 🎯 Category filtering
- 🔖 Bookmark system
- 💾 Local storage support
- 🌐 Responsive design

## 📄 License

MIT License - feel free to use and modify!

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

---

**Note**: The first time you run the app, it may take a moment to load. Make sure you have an internet connection for external resources like Font Awesome icons.
