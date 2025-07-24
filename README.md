# Streamer Helper

Your streaming companion 💛

A modern desktop application designed to help streamers simplify OBS management, and remote control your OBS streaming workflow from a unified dashboard.

## Quick Start

1. **Download** the application from the link below
2. **Install** run Streamer Helper installer
3. **Connect to OBS**: Ensure OBS Studio is running with WebSocket enabled
4. **Authenticate with Twitch**: Use the built-in OAuth flow to connect your Twitch account
5. **Start Streaming**: Use the dashboard to control your stream

## Downloads

Steamer Helper Homepage > [Streamer Helper](https://bobjames.dev/apps/streamer-helper)  

Windows Installer   : [Streamer Helper Setup 0.1.91.exe](https://github.com/bbbjames/streamer-helper/releases/download/v0.1.91-beta-release/Streamer.Helper.Setup.v0.1.91.exe)  
SHA256      : 7373A24FADAD8AB3C101A20651A95846051FB5CC38BC064D694C5BE64C50E645

MacOS   : (coming soon)  
Linux   : (coming soon)

![Streamer Helper](https://img.shields.io/badge/version-0.1.91-blue.svg)

## Features

### 🎥 OBS Studio Integration
- **WebSocket Connection**: Seamless integration with OBS Studio via WebSocket
- **Stream Control**: Start/stop streaming directly from the app
- **Scene Management**: Visual scene previews and switching
- **Performance Monitoring**: Real-time OBS performance metrics

### 📊 Twitch Integration
- **OAuth Authentication**: Secure Twitch login
- **Live Statistics**: Real-time viewer count and follower tracking
- **Stream Status**: Monitor your Twitch stream status
- **Commercial Controls**: Run commercials with customizable durations

### 🎨 Modern Interface
- **Glass Morphism Design**: Beautiful, modern UI with backdrop blur effects
- **Theme System**: Dynamic theming with visual effects
- **Responsive Layout**: Optimized for different screen sizes
- **Real-time Updates**: Live data updates without page refresh

### 🔧 Additional Tools
- **Chat Integration**: Built-in chat display and management
- **Auto-updater**: Automatic application updates

### ⚡ Additional Dev/Features Requests
- **Twitch Features**: Edit Category and Stream Title
- **Notes App**: in app Notes App
- **Social Media**: Quick social media capabilities
- **Restream Capabilities**: Video feed restreamer
- **Authenticode + Code Signing**: Microsoft Authenticode + Trusted Signing

## Technology Stack

- **Desktop Framework**: Electron 37.2.0
- **Frontend**: Next.js with React
- **Styling**: Tailwind CSS with custom glass morphism effects
- **Real-time Communication**: WebSocket (OBS) and REST APIs (Twitch)
- **Build System**: Electron Builder for cross-platform distribution

## System Requirements

- **Windows**: Windows 10 or later
- **macOS**: macOS 10.14 or later
- **Linux**: Ubuntu 18.04 or equivalent
- **OBS Studio**: Version 28.0 or later
- **Memory**: 4GB RAM recommended
- **Storage**: 200MB available space

## Key Components

### Stream Dashboard
- Live stream status and controls
- Real-time viewer metrics
- OBS performance monitoring
- Quick action buttons

### Scene Manager
- Visual scene previews with thumbnails
- One-click scene switching
- Scene organization tools

### Settings Panel
- OBS WebSocket configuration
- Twitch API settings
- UI customization options
- Update management

## Development

The application is built with:
- **Main Process**: TypeScript with Electron
- **Renderer Process**: Next.js with TypeScript and Tailwind CSS
- **Build Tools**: Webpack and Electron Builder

---

## License

This software is released under the Bob James Software License (BJSL) EULA Version 1.0.

See [LICENSE.txt](./LICENSE.txt) or https://bobjames.dev/articles/licenses/bjsl-v1 for the full terms.

**Bob James Software Licence EULA v1.0 Copyright © 2025 Business and Research Ltd**  

For apps and updates, visit [bobjames.dev](https://bobjames.dev/apps)

For Streamer Helper issues, support and feature requests please use our [GitHub
Issues](https://github.com/bbbjames/streamer-helper/issues) page.
