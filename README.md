# ShotIt - Public Updates

This repository hosts auto-update files for **ShotIt** - a macOS screenshot tool.

## 📦 What's here?

- `appcast/appcast.xml` - Sparkle update feed
- GitHub Releases contain notarized `.zip` packages

## 🔄 How updates work

1. ShotIt app checks this appcast.xml for new versions
2. If update available, downloads .zip from GitHub Releases
3. Verifies EdDSA signature
4. Installs update automatically

## 🔒 Security

All updates are:
- ✅ Signed with Apple Developer ID
- ✅ Notarized by Apple
- ✅ Signed with EdDSA key (verified by Sparkle)

## 📥 Download

Get the latest version from [Releases](https://github.com/hai199580/ShotIt-pub/releases)

---

🤖 This repo is automatically maintained by release scripts.
