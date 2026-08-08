<p align="center">
  <img src="knowledge_book.png" width="110" alt="Knowledge Book" />
</p>

<h1 align="center">RyanWare Meteor Addon</h1>
<p align="center"><strong><span style="color:#7c3aed">Meteor Client</span> addon with advanced modules, automation, and powerful utilities.</strong></p>

<p align="center">
  <span style="color:#22c55e"><strong>Automation</strong></span> •
  <span style="color:#f97316"><strong>Combat</strong></span> •
  <span style="color:#38bdf8"><strong>Chat</strong></span> •
  <span style="color:#ec4899"><strong>Entertainment</strong></span> •
  <span style="color:#a855f7"><strong>AI</strong></span> •
  <span style="color:#facc15"><strong>Utility</strong></span> •
  <span style="color:#ef4444"><strong>Experimental</strong></span>
</p>

<p align="center">
    [<a href="https://github.com/SmilerRyan/Meteor-RyanWare">GitHub</a>] •
    [<a href="https://github.com/SmilerRyan/Meteor-RyanWare/archive/refs/heads/main.zip">Download zip</a>] •
    [<a href="#installation">Install</a>] •
    [<a href="https://github.com/SmilerRyan/Meteor-RyanWare/commits/main/">Changelog</a>]
</p>

---

## 🚀 Project Overview

**RyanWare** is a feature-rich Meteor Client addon that extends Minecraft with a wide range of modules, commands, and intelligent utilities.

This addon is designed to run on top of Meteor Client and is not a standalone client. It is built for the latest Minecraft + Meteor Client versions and is best used with the current supported releases.

> <span style="color:#f59e0b"><strong>Note:</strong></span> Some modules are experimental, server-dependent, or intended for learning and testing. Use responsibly and avoid deploying features on servers where they may violate rules.

---

## ✨ Key Features

- <span style="color:#34d399">Automation</span>: auto-mine, auto-follow, auto-click, auto-groom, and more
- <span style="color:#fb7185">Combat Enhancements</span>: aura, anti-block, auto-attack, and targeted utilities
- <span style="color:#60a5fa">Chat Tools</span>: auto chat screenshotter, auto responder, commands, and chat helpers
- <span style="color:#fbbf24">Utility Modules</span>: item frame dupe, chest mover, highway builder, teleport tools
- <span style="color:#c084fc">AI & Experimental</span>: smart responders, module experiments, and developer-focused tools
- Easy build support for both addon and standalone packaging

---

## 📦 Installation

### Option A: Addon mode
1. Install Meteor Client.
2. Build RyanWare or download the addon JAR from GitHub.
3. Place both Meteor Client and `RyanWare-addon.jar` into `.minecraft/mods`.
4. Launch Minecraft using Fabric.

### Option B: Standalone mode
1. Download `RyanWare-standalone.jar` from GitHub.
2. Place it in `.minecraft/mods`.
3. Launch Minecraft with Fabric (recommended Fabric 1.21.11 for best compatibility).

> <span style="color:#2563eb"><strong>Recommended:</strong></span> Use the latest Meteor Client version available and keep the addon updated alongside Meteor.

---

## 🛠️ Building from Source

Required tools:
- Java 21 JDK
- Gradle 8.13

Build command:

```bash
./gradlew clean build --no-daemon
```

Expected output:

```text
./build/libs/meteor-RyanWare-0.1-addon.jar
./build/libs/meteor-RyanWare-0.1-standalone.jar
```

---

## 📁 Recommended Setup

For a clean environment:
- Use a fresh Fabric installation.
- Keep Meteor Client and RyanWare in `.minecraft/mods`.
- Back up game saves before testing experimental modules.

---

## 🧠 Compatibility

- Target platform: Minecraft + Meteor Client
- Best used with the latest supported Meteor Client build
- Standalone build ships with embedded Meteor Client support
- Older game or client versions may work but are not officially supported

---

## ⚖️ License and Credits

Licensed under **GPL v3**.

You are required to:
- open-source derivative projects
- preserve the same license
- credit the original project when using this code

Credits:
- Meteor Development Team — Meteor Client and API foundation
- AntiCope — base inspiration from Meteor Crash Addon
- ChatGPT & AI tools — development assistance
- All RyanWare contributors — testing, suggestions, and code

---

## 📝 Notes

- This addon is built for experimentation and utility.
- Some modules may be flagged as cheating on multiplayer servers.
- Use with care and respect community/server rules.
