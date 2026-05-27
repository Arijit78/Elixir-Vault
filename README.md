# Elixir Vault

Elixir Vault is a modern, high-performance Android download manager and browser utility designed for simplicity, speed, and advanced control.

## ✨ Features

- **Integrated Browser**:
    - Multi-tab support.
    - **Customizable Search Engines**: Support for Google, DuckDuckGo, Bing, and Brave.
    - **Search in Page**: Find specific text within any webpage.
    - **Privacy First**: Ad-blocker and JavaScript toggle.
    - **Independent Themes**: Set a different theme for the browser (Light, Dark, AMOLED) independent of the app's theme.
    - **Home & Home Navigation**: Quickly jump to your selected search engine's home page.

- **Optimized for SourceForge**: 
    - Auto-select best mirrors.
    - Skip intrusive ad pages.
    - Direct link extraction for faster starts.

- **Powerful Download Management**: 
    - **Multi-part Downloading**: Accelerate downloads with multiple connections per file (up to 32 connections).
    - **Custom Directory**: Full control over where your files are saved.
    - **Auto-Organize**: Group downloads into subfolders by file type (Video, Audio, Docs, etc.).
    - **Smart Conflict Resolution**: Rename, Overwrite, or Skip duplicate files.
    - **Integrity Verification**: Automatic MD5/SHA check after download completion.
    - **Network Control**: WiFi-only mode and global speed limits to save data and bandwidth.
    - **File Type Icons**: Visual identification of files (Video, Music, PDF, APK, etc.).
    - **Status Badges**: Real-time download state reflected directly on file icons.

- **Modern & Adaptive UI**:
    - Built using **Jetpack Compose** with **Material 3**.
    - **Dynamic Theming**: Supports System, Light, Dark, and **AMOLED (Pure Black)** modes.
    - **Edge-to-Edge**: Fully immersive experience with transparent system bars.
    - **Adaptive Layouts**: Support for different screen sizes and orientations.
    - **Network Status Indicator**: Real-time monitoring of connection type (WiFi/Mobile/Disconnected) in the dashboard.

- **Security & Performance**:
    - **Biometric Lock**: Secure the entire app with Fingerprint, Face, or Device Credentials.
    - **Proxy Support**: Configure HTTP/SOCKS proxies for secure or restricted browsing.
    - **Low Overhead**: Optimized with R8/ProGuard for a tiny app footprint and high performance.

- **Deep Customization**:
    - **Multi-language**: Interface available in English, Spanish, French, German, Hindi, and Indonesian.
    - **Advanced Notifications**: Separate toggles for completion sounds, vibration, and LED alerts.
    - **Storage Insights**: Real-time view of internal storage and cache management.
    - **App Restart**: Easy one-tap restart from settings to apply low-level changes.

## 🛠️ Technical Details

- **Language**: Kotlin
- **UI Framework**: Jetpack Compose (Material 3)
- **Networking**: OkHttpClient with dynamic Proxy support and custom connection timeouts.
- **Database**: Room for metadata, download history, and browser bookmarks/history.
- **State Management**: Jetpack DataStore (Preferences) for persistent settings.
- **Navigation**: Type-safe navigation using Kotlin Serialization.

## 🚀 Getting Started

1. **Launch**: Open Elixir Vault and grant necessary permissions.
2. **Search**: Use the **Explore** button to start browsing with your preferred search engine.
3. **Download**: Long-press links or use the "Direct Link" button to start a download.
4. **Manage**: Monitor progress in the **Dashboard** and view finished files in the **Library**.
5. **Personalize**: Head to **Settings** to tweak themes, network limits, and security.

## 👷 Built by
**Arijit Saha**
