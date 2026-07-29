<div align="center">

# 🚀 Blue Uploader Compressor

### Professional Texture Optimisation for Unity & VRChat

*A powerful Unity Editor extension designed to optimise textures, reduce project size, and safely restore original import settings.*

![Unity](https://img.shields.io/badge/Unity-2022.3%2B-black?style=for-the-badge&logo=unity)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS-blue?style=for-the-badge)
![Language](https://img.shields.io/badge/C%23-100%25-purple?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-brightgreen?style=for-the-badge)

---

### ⚡ Compress Hundreds of Textures in Seconds — Without Losing Your Original Settings

</div>

---

# 📖 About

Blue Uploader Compressor is a **professional Unity Editor tool** created and maintained solely by **Alan Grant**.

It was built to solve one of the biggest frustrations in Unity and VRChat development—optimising hundreds of textures manually.

Instead of spending hours adjusting texture import settings one file at a time, Blue Uploader Compressor automates the entire process while ensuring every original setting can be restored at any time.

Whether you're preparing a VRChat avatar, optimising a game, or reducing project size, the tool makes the workflow significantly faster and safer.

---

# ✨ Features

## 🚀 Batch Optimisation

- Optimise entire Unity projects
- Process hundreds of textures in one click
- Massive time savings

---

## 💾 Automatic Backups

Every optimisation creates a complete backup before making changes.

Restore:

- Texture Size
- Compression Quality
- Compression Mode
- Read/Write
- Mip Maps
- Crunch Compression

Nothing is permanently lost.

---

## 🎨 Smart Compression

Configure:

- Maximum Texture Size
- Compression Quality
- Compression Format
- Mip Maps
- Read/Write
- Crunch Compression

---

## 🔄 One Click Restore

Changed your mind?

Simply load one of your backups and restore every texture to its original Unity import settings.

---

## 📦 Lightweight

- Fast
- Clean
- No unnecessary dependencies
- Works directly inside the Unity Editor

---

# 📊 Why Use Blue Uploader Compressor?

| Without | With |
|---------|------|
| Edit every texture manually | One-click optimisation |
| Easy to forget settings | Automatic backups |
| Hours of repetitive work | Complete in minutes |
| Difficult to undo | Instant restore |
| Inconsistent settings | Consistent optimisation |

---

# 🛡 Safety First

Blue Uploader Compressor **never blindly overwrites your project.**

Before any texture is modified, the tool stores every important import setting inside a backup file.

That means you can freely experiment with optimisation knowing you can always return to the original configuration.

---

# ⚙️ Installation

1. Download the latest release.
2. Import the package into your Unity project.
3. Open:

```
Tools
└── Blue Uploader Compressor
```

4. Configure your optimisation settings.
5. Press **Compress**.

---

# 📁 Backup Format

Each backup stores information including:

```json
{
    "createdAt": "...",
    "entries": [
        {
            "path": "...",
            "maxTextureSize": 2048,
            "compressionQuality": 50,
            "mipmapEnabled": true,
            "isReadable": false,
            "crunchedCompression": false,
            "textureCompression": 1
        }
    ]
}
```

---

# 🖼 Screenshots

> Coming Soon

Dashboard

Compression Window

Restore Window

Progress Window

Statistics

---

# 🗺 Roadmap

- [ ] Modern Dashboard
- [ ] Folder Profiles
- [ ] Presets
- [ ] Texture Analysis
- [ ] Duplicate Texture Detection
- [ ] Memory Usage Report
- [ ] Optimisation Score
- [ ] Drag & Drop Support
- [ ] Theme System
- [ ] Search & Filter
- [ ] Texture Preview
- [ ] Multi-threaded Processing

---

# 🤝 Contributing

Bug reports, feature suggestions and pull requests are always welcome.

If you've found an issue or have an idea for a new feature, feel free to open an Issue.

---

# 👨‍💻 Developer

## Bluey Barks

Blue Uploader Compressor is an independent project designed, programmed and maintained entirely by **Alan Grant**.

Every line of code, the editor interface, optimisation system and backup workflow have been developed specifically for this project.

---

# ❤️ Support

If this project has helped you, consider:

⭐ Starring the repository

🐞 Reporting bugs

💡 Suggesting features

📢 Sharing it with other Unity developers

---

<div align="center">

## Thank you for using Blue Uploader Compressor!

**Made with ❤️ by Alan Grant**

</div>
