# Messenger for Desktop

A simple desktop application wrapper for Google Messages for Web, built with Electron.

## Features

- Access Google Messages directly from your desktop
- Native desktop application experience
- No API keys required
- Works just like the web version

## Installation

I have included pre-built versions in the [releases](https://github.com/ChapDaddy65/MessagesForDesktop/releases) section, otherwise feel free to continue with building the app yourself.

1. Clone this repository:
```bash
git clone https://github.com/yourusername/MessagesForDesktop.git
cd MessagesForDesktop
```

2. Install dependencies:
```bash
npm install
```

3. Run the application:
```bash
npm start
```

## Building

To create distributable packages for all platforms:
```bash
npm run build
```

### Platform-Specific Builds

Build only for Linux:
```bash
npm run build:linux
```

Build only for Windows:
```bash
npm run build:windows
```

### Available Build Formats

#### Linux
- AppImage (portable, runs on most distributions)
- DEB (Ubuntu, Debian)
- RPM (Fedora, RHEL)
- Pacman (Arch Linux)
- tar.gz (generic Linux package)

#### Windows
- NSIS (Windows installer)
- Portable EXE
- ZIP archive

The build outputs will be created in the `dist` directory.

## License

ISC 