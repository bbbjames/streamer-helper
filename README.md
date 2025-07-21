# Streamer Helper

Your streaming companion 💛

A modern desktop application designed to help streamers simplify OBS management, and remote control their OBS streaming workflow from a unified dashboard.

## Quick Start

1. **Download** the application from the link below
2. **Install** run Streamer Helper installer
3. **Connect to OBS**: Ensure OBS Studio is running with WebSocket enabled
4. **Authenticate with Twitch**: Use the built-in OAuth flow to connect your Twitch account
5. **Start Streaming**: Use the dashboard to control your stream

## Downloads

Steamer Helper Homepage + Downloads > [Streamer Helper](https://bobjames.dev/apps/streamer-helper)

Windows Installer   : [Streamer Helper Setup 0.1.91.exe](https://github.com/bbbjames/streamer-helper/releases/download/streamer-helper-v0.1.91-beta-release/Streamer.Helper.Setup.0.1.91.exe)

MD5 Hash    : C370CA18EE50471362D0579A0028A2E5

SHA256      : 755039BC9F9B0A178AFD56055F4096C9E8516267D6F4DA9F84D17DF319352B3B

![Streamer Helper](https://img.shields.io/badge/version-0.1.91-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)

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

**Copyright © 2025 Bob James**  
For apps and updates, visit [bobjames.dev](https://bobjames.dev/apps)
For Streamer Helper issues, support and feature requests please use our [GitHub
Issues](https://github.com/bbbjames/streamer-helper/issues) page.
