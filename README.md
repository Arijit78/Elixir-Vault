# Elixir Vault 🛡️

**Elixir Vault** is a high-performance, secure, and privacy-focused download manager for Android. It combines advanced multi-part download technology with a built-in secure browser and AI-driven intelligence to provide a seamless downloading experience.

## ✨ Features

### 🚀 Core Download Engine
- **Multi-part Downloading**: Accelerate downloads by splitting files into multiple segments.
- **Dynamic Speed Optimization**: Automatically adjusts connections for maximum throughput.
- **Smart Pause & Resume**: Reliable resumption of interrupted downloads.
- **Background Downloads**: Keep downloading even when the app is closed.
- **Intelligent Direct Link Handling**: Pasting a direct download link (MP4, APK, ZIP, etc.) in the search bar triggers an instant verification screen and immediate download overlay.
- **Improved Extension Detection**: Intelligent mapping of server MIME types to correct file extensions, fixing issues with script-spoofed files (.php, .bin, etc.).

### 🎥 Media & Torrents
- **BitTorrent Support**: Full support for `.torrent` files and `magnet:` links powered by `jlibtorrent` 2.0.12.9.
- **Modern NDK Integration**: Built with 16KB page size support for compatibility with the latest Android devices and Google Play standards.
- **In-App Media Player**: Play downloaded videos and music directly within the app.
- **Organized Library**: Automatically categorizes files by type (Movies, Music, Archives, etc.).

### 🌐 Seamless Secure Browser
- **Per-Tab Incognito Mode**: Open normal and private tabs simultaneously. Toggle privacy status for any tab instantly from the options menu.
- **Smart Search Bar**: 
    - **Auto-Clear**: Clears automatically on focus for a fresh entry.
    - **Clipboard Integration**: Shows a preview of your last copied link as a hint.
    - **Quick Paste**: Dedicated button to instantly paste text/links from your clipboard.
    - **Intelligent Restore**: Automatically restores the original URL if browsing is continued without a new search.
- **Ad-Blocker**: Built-in protection against intrusive ads and trackers.
- **Privacy Mode**: Integrated VPN support and custom DNS settings for anonymous browsing.
- **Clean Interface**: Navigation drawer is automatically disabled in browsing mode to maximize focus.

### 🧠 Ultron AI (Now with Voice!)
- **Groq Integration**: Powered by Llama 3.3 70B for lightning-fast, professional technical assistance.
- **Voice Commands**: Just tap the mic and say **"Download this video"** or **"Download this link"** to automatically initiate a download from the conversation context.
- **Technical Specialist**: Help you find content, summarize pages, and manage your vault using natural language.

### 🛡️ Security & Performance
- **Biometric Lock**: Secure your entire library with fingerprint or face unlock.
- **Exit Protection**: Confirmation dialogs for both the Browser and the Main Dashboard to prevent accidental closures.
- **Memory Optimized**: Throttled UI updates, efficient I/O buffering (16KB), and proactive memory management.
- **App Updater**: Built-in update engine with persistent indicators and easy installation via a redesigned "What's New" section.
- **Modern UI**: Material You design with True Black AMOLED theme support and glassmorphism elements.

## 🛠️ Tech Stack
- **Language**: Kotlin 1.9+
- **UI Framework**: Jetpack Compose
- **Groq AI**: Llama 3.3 via Retrofit.
- **Local Storage**: Room Database & DataStore Preferences.
- **Networking**: OkHttp 4 & `jlibtorrent` (Native C++ Engine).

---
*Designed and Developed by [Arijit Saha](https://github.com/Arijit78)*
