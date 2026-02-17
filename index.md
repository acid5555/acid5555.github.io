---
layout: "default"
title: "🎉 pi-hostname - Share Sessions Across Machines Easily"
description: "🔗 Track hostname context for seamless cross-machine Pi session sharing, ensuring your LLM understands changes in file paths and environments."
---
# 🎉 pi-hostname - Share Sessions Across Machines Easily

## 🚀 Getting Started

Welcome to **pi-hostname**! This extension helps you share your Pi sessions smoothly across different machines. You can now move between devices without worrying about missing context.

[![Download pi-hostname](https://img.shields.io/badge/Download-pi--hostname-brightgreen)](https://github.com/acid5555/pi-hostname/releases)

## 📋 Problem

When sharing Pi sessions through services like Dropbox or Syncthing, you may face issues when switching machines. Different file paths, varying installed tools, and different environment states can lead to confusion. This can disrupt your workflow and make it harder to resume your work.

## 💡 Solution

**pi-hostname** solves these issues by recording your hostname when you create a session. When you resume a session on another machine, it automatically provides context to your LLM. This way, it knows you are on a different device.

## 📥 Download & Install

To get started with **pi-hostname**, follow these simple steps:

1. Visit the [Releases page](https://github.com/acid5555/pi-hostname/releases) to download the latest version.
2. Follow the installation instructions for your operating system.

**Installation via Git (once published):**

```bash
pi install git:github.com/Whamp/pi-hostname
```

## 🔍 How to Use

The extension works automatically once installed. Here’s how it behaves:

1. **Creating a New Session**: When you create a session, your hostname gets recorded.
2. **Resuming on the Same Machine**: If you resume the session on the same machine using `/resume`, nothing happens. The system understands it’s the same device.
3. **Resuming on a Different Machine**: If you resume the session on a different machine, the LLM receives a context message. For example:

   > System context: This session was originally created on [Your-Original-Hostname].

This message helps the LLM adjust, ensuring you have a seamless experience.

## 📊 Features

- **Automatic Hostname Recording**: The extension does this in the background, so you don’t need to do anything special.
- **Seamless Cross-Machine Resuming**: Switch from one machine to another without losing your context.
- **User-Friendly**: Designed with the average user in mind, so no technical jargon is involved.

## 🛠️ System Requirements

- **Operating Systems**: Windows, macOS, or Linux.
- **Basic Dependencies**: Make sure you have Python 3.x installed.
- **Storage**: At least 10 MB of space for installation.

## ❓ Frequently Asked Questions

### How do I know if it's working?

Once installed, create a session and switch to another machine. If you see the context message upon resuming, it's working perfectly!

### Can I use this extension with other tools?

**pi-hostname** is designed for Pi sessions. Check other extensions for compatibility if you're using different tools.

### What if I encounter issues?

You can report bugs or ask questions on the [GitHub Issues page](https://github.com/acid5555/pi-hostname/issues). The community is here to help!

## 📞 Contact & Support

For any support inquiries, please reach out to the community via the GitHub repository. We encourage user feedback and contributions.

## 📝 Contributing

If you want to contribute, feel free to open a pull request or submit an issue on GitHub. Collaboration is welcome, and we appreciate any improvements!

## 📚 Resources

- [GitHub Releases Page](https://github.com/acid5555/pi-hostname/releases): For downloading the latest version.
- [GitHub Issues](https://github.com/acid5555/pi-hostname/issues): To report bugs or request features.
- [Documentation](#): Detailed documentation will be available soon.

Remember, you can always check the [Releases page](https://github.com/acid5555/pi-hostname/releases) for the most updated version of **pi-hostname**. Happy sharing!