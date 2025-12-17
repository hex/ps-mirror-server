# Mirror for Photoshop Server

WebSocket relay server for Mirror for Photoshop - bridges Photoshop to iOS for real-time preview.

## Installation

### macOS

**Homebrew (recommended):**

```bash
brew tap hex/mirror-for-photoshop
brew install mirror-for-photoshop-server
```

**Direct Download:**

Download the appropriate binary from [releases](https://github.com/hex/mirror-for-photoshop-server/releases):
- `mirror-for-photoshop-server-macos-arm64` for Apple Silicon (M1/M2/M3/M4)
- `mirror-for-photoshop-server-macos-x64` for Intel Macs

Make executable and run:
```bash
chmod +x mirror-for-photoshop-server-macos-*
./mirror-for-photoshop-server-macos-arm64  # or -x64 for Intel
```

### Windows

**Winget (pending approval):**

```powershell
winget install Hex.MirrorForPhotoshopServer
```

**Direct Download:**

Download `mirror-for-photoshop-server-win-x64.zip` from [releases](https://github.com/hex/mirror-for-photoshop-server/releases), extract, and run the executable.

## Usage

The server starts on port 8765 and advertises via Bonjour/mDNS for automatic discovery by the iOS app.

## More Information

Visit [mirrorps.hexul.com](https://mirrorps.hexul.com) for the iOS app and Photoshop plugin.
