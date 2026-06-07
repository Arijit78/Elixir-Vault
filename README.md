# Elixir Vault 🛡️

**Elixir Vault** is a high-performance, secure, and privacy-focused download manager for Android. It combines advanced multi-part download technology with a built-in secure browser and AI-driven intelligence to provide a seamless downloading experience.

## ✨ Features

### 🚀 Core Download Engine
- **Multi-part Downloading**: Accelerate downloads by splitting files into multiple segments.
- **Dynamic Speed Optimization**: Automatically adjusts connections for maximum throughput.
- **Smart Pause & Resume**: Reliable resumption of interrupted downloads.
- **Background Downloads**: Keep downloading even when the app is closed.
- **Improved Extension Detection**: Intelligent mapping of server MIME types to correct file extensions.

### 🎥 Media & Torrents
- **BitTorrent Support**: Full support for `.torrent` files and `magnet:` links powered by `jlibtorrent` 2.x.
- **In-App Media Player**: Play downloaded videos and music directly within the app.
- **Organized Library**: Automatically categorizes files by type (Movies, Music, Archives, etc.).

### 🌐 Secure Browser
- **Ad-Blocker**: Built-in protection against intrusive ads and trackers.
- **Privacy Mode**: Integrated VPN support and custom DNS settings.
- **Clean Experience**: Navigation drawer is disabled in browsing mode for a focused view.

### 🧠 Ultron AI (Now with Voice!)
- **Groq Integration**: Powered by Llama 3.3 for lightning-fast, professional assistance.
- **Voice Commands**: Just tap the mic and say "Download this video" to initiate a download from the conversation context.
- **Technical Specialist**: Help you find content, summarize pages, and manage your vault.

### 🛡️ Security & Performance
- **Biometric Lock**: Secure your library with fingerprint or face unlock.
- **Memory Optimized**: Throttled UI updates and efficient I/O buffering for low resource consumption.
- **Modern UI**: Material You design with True Black AMOLED theme support.

## 🛠️ Tech Stack
- **Language**: Kotlin 1.9+
- **UI Framework**: Jetpack Compose (Modern Declarative UI)
- **Groq AI**: Llama 3.3 70B via Retrofit.
- **Local Storage**: Room Database & DataStore.
- **Networking**: OkHttp 4 & `jlibtorrent` 2.0.12.9.

---
*Designed and Developed by [Arijit Saha](https://github.com/Arijit78)*
