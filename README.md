# Elixir Vault 🛡️

**Elixir Vault** is a high-performance, secure, and privacy-focused download manager for Android. It combines advanced multi-part download technology with a built-in secure browser and AI-driven intelligence to provide a seamless downloading experience.

## ✨ Features

### 🚀 Core Download Engine
- **Multi-part Downloading**: Accelerate downloads by splitting files into multiple segments.
- **Dynamic Speed Optimization**: Automatically adjusts connections for maximum throughput.
- **Smart Pause & Resume**: Reliable resumption of interrupted downloads.
- **Background Downloads**: Keep downloading even when the app is closed.
- **Improved Extension Detection**: Intelligent mapping of server MIME types to correct file extensions, fixing issues with script-spoofed files (.php, .bin, etc.).

### 🎥 Media & Torrents
- **BitTorrent Support**: Full support for `.torrent` files and `magnet:` links powered by `jlibtorrent` 2.0.12.9.
- **Modern NDK Integration**: Built with 16KB page size support for compatibility with the latest Android devices and Google Play standards.
- **In-App Media Player**: Play downloaded videos and music directly within the app.
- **Organized Library**: Automatically categorizes files by type (Movies, Music, Archives, etc.).

### 🌐 Secure Browser
- **Ad-Blocker**: Built-in protection against intrusive ads and trackers via custom DNS and logic.
- **Privacy Mode**: Integrated VPN support and custom DNS settings for anonymous browsing.
- **Clean Interface**: Navigation drawer is automatically disabled in browsing mode to maximize screen space and focus.
- **Exit Confirmation**: Safeguard your browsing session with a confirmation dialog before returning to the dashboard.
- **Redesigned Options**: Sleek, fully rounded Material 3 menu for bookmarks, history, and desktop mode.

### 🧠 Ultron AI (Now with Voice!)
- **Groq Integration**: Powered by Llama 3.3 70B for lightning-fast, professional technical assistance.
- **Voice Commands**: Just tap the mic and say **"Download this video"** or **"Download this link"** to automatically initiate a download from the conversation context.
- **Technical Specialist**: Help you find content, summarize pages, and manage your vault using natural language.

### 🛡️ Security & Performance
- **Biometric Lock**: Secure your entire library with fingerprint or face unlock.
- **Memory Optimized**: Throttled UI updates, efficient I/O buffering (16KB), and proactive memory management.
- **App Updater**: Built-in update engine with persistent indicators and easy installation.
- **Modern UI**: Material You design with True Black AMOLED theme support and glassmorphism elements.

## 🛠️ Tech Stack
- **Language**: Kotlin 1.9+
- **UI Framework**: Jetpack Compose
- **Groq AI**: Llama 3.3 via Retrofit.
- **Local Storage**: Room Database & DataStore Preferences.
- **Networking**: OkHttp 4 & `jlibtorrent` (Native C++ Engine).

---
*Designed and Developed by [Arijit Saha](https://github.com/Arijit78)*
