<!-- Header Section -->
# DeepSeek Desktop Version ![MIT License](https://img.shields.io/badge/License-MIT-green.svg) ![Windows](https://img.shields.io/badge/Windows-Support-0078D6) ![macOS](https://img.shields.io/badge/macOS-Support-000000)

**Unofficial Privacy-Focused Desktop Client for DeepSeek AI** - Native experience with offline-first design

[![GitHub release](https://img.shields.io/github/v/release/devedale/deepseek-desktop-version)](https://github.com/devedale/deepseek-desktop-version/releases)
[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/devedale/deepseek-desktop-version/build.yml)](https://github.com/devedale/deepseek-desktop-version/actions)


<!-- Stars Callout -->
<div align="center">
  <h3>🌟 Support Open Source!</h3>
  <p>If this project helps you, please consider giving it a star!<br>Your support helps maintain and improve this educational codebase.</p>
  <a href="https://github.com/devedale/deepseek-desktop-version/stargazers">
    <img src="https://img.shields.io/github/stars/devedale/deepseek-desktop-version?style=for-the-badge&logo=github">
  </a>
</div>

<!-- Downloads Section -->
<div align="center">
  <a href="https://www.buymeacoffee.com/devedale" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Coffee" style="height: 40px !important;width: 145px !important;" ></a>
</div>


## 🚀 Instant Installation

| Platform | Download | Size | Checksum |
|----------|----------|------|----------|
| Windows  | [Windows Installer](https://github.com/devedale/deepseek-desktop-version/blob/main/dist/windows/Deepseek%20Chat%20Setup%201.0.0.exe) | 82 MB | [Verify](https://github.com/devedale/deepseek-desktop-version/blob/main/dist/windows/checksums.txt) |
| macOS    | [macOS Intaller](https://github.com/devedale/deepseek-desktop-version/blob/main/dist/mac/Deepseek%20Chat-1.0.0-arm64.dmg) | 89 MB | [Verify](https://github.com/devedale/deepseek-desktop-version/blob/main/dist/mac/checksums.txt) |

*Why EXE/DMG files?*  
Our native packages include everything needed for:  
✅ Instant launch without dependencies  
✅ Hardware-optimized performance  
✅ Secure execution environment  

<!-- Features Section -->
## 🔥 Top Features
- **Zero Tracking** - All data stays on your device
- **Lightning Fast** - Native C++ core with WebView interface
- **Encrypted Storage** - Local SQLite database with AES-256
- **Cross-Platform** - Windows + macOS support (ARM/x64)
- **Portable Mode** - Run from USB drive without installation

<!-- Build Section -->
## 🛠️ GitHub-Powered Builds

Our automated workflow makes compilation effortless:

1. Push code to any branch
2. GitHub Actions automatically:
   - Compiles native binaries
   - Generates installers
   - Signs executables (if configured)
   - Publishes to Releases
3. Download from [Releases Page](https://github.com/devedale/deepseek-desktop-version/releases)

<!-- Contribution Section -->
## 👩💻 Become a Contributor!

This minimalist codebase is perfect for learning native development:
```
src/
├── main.cpp           // Native entry point
├── webview/           // System WebView wrapper
├── security/          // Encryption modules
└── storage/           // Local database handling
```

We welcome all improvements!  
🔧 Fix typos in docs  
🛠️ Optimize build scripts  
🔐 Enhance security modules  

<!-- FAQ Section -->
## ❓ Essential FAQ

**Q: Why large EXE files?**  
A: Contains all native dependencies - no runtime installations needed!

**Q: Safe to run?**  
A: 100% transparent code - compile yourself or verify checksums

**Q: Data location?**  
Windows: %LOCALAPPDATA%\DeepSeekDesktop  
macOS: ~/Library/Caches/DeepSeek

<!-- Footer Section -->
## 📜 License & Community
MIT Licensed - Free for personal/commercial use. Help us grow:  
- ⭐ Star the repository  
- 🐛 Report issues  
- 📣 Share with colleagues  

*Not affiliated with DeepSeek Inc. DeepSeek® is a registered trademark.*

[![Star History Chart](https://api.star-history.com/svg?repos=devedale/deepseek-desktop-version&type=Date)](https://star-history.com/#devedale/deepseek-desktop-version&Date)
