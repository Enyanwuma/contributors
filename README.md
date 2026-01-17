# 🐉 Contribution Matrix PRO

<div align="center">

![Version](https://img.shields.io/badge/version-3.0-00ff9d?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-00ff9d?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-00ff9d?style=for-the-badge&logo=javascript)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**An interactive GitHub-style contribution tracker with 15+ advanced features**

[Live Demo](#) • [Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Achievements](#-achievements)

![Contribution Matrix Pro Banner](https://via.placeholder.com/1200x400/0c0c1d/00ff9d?text=Contribution+Matrix+PRO)

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Demo](#-demo)
- [Installation](#-installation)
- [Usage Guide](#-usage-guide)
- [Keyboard Shortcuts](#-keyboard-shortcuts)
- [Themes](#-themes)
- [Achievements System](#-achievements-system)
- [Technical Details](#-technical-details)
- [Browser Support](#-browser-support)
- [Contributing](#-contributing)
- [License](#-license)
- [Credits](#-credits)

---

## 🎯 Overview

**Contribution Matrix PRO** is an enhanced, interactive version of GitHub's contribution graph. It transforms the familiar green squares into a creative playground with drawing tools, pattern generators, undo/redo functionality, and an achievement system.

### 🌟 Why Use This?

- **Creative Expression**: Design custom patterns and artwork
- **GitHub Profile Enhancement**: Export and share your creations
- **Learning Tool**: Understand contribution patterns visually
- **Fun & Interactive**: Gamified with achievements and challenges
- **No Dependencies**: Pure vanilla JavaScript - no frameworks required

---

## ✨ Features

### 🎨 Core Features

| Feature | Description |
|---------|-------------|
| **🖌️ Draw Mode** | Click and drag to paint across cells |
| **↩️ Undo/Redo** | Full history navigation (50 states) |
| **📥 Export to Image** | Download your creation as PNG |
| **🎭 3 Themes** | Van_Dragon, Dragonfire, Cybervoid |
| **💾 Auto-Save** | Never lose your progress |
| **📊 Real-Time Stats** | Track contributions, streaks, changes |
| **🏆 10 Achievements** | Unlock rewards for milestones |
| **🎯 Intensity Selector** | Choose brush strength (0-4) |
| **⌨️ Keyboard Shortcuts** | Power-user efficiency |
| **📱 Responsive Design** | Works on all screen sizes |

### 🎨 Pattern Library (10 Presets)

```
┌─────────────────────────────────────────────┐
│  ✓ Checkerboard  ✓ Wave       ✓ Diagonal   │
│  ✓ Heart         ✓ Smile      ✓ Gradient   │
│  ✓ Circle        ✓ Border     ✓ Spiral     │
│  ✓ Cross         ... and more!              │
└─────────────────────────────────────────────┘
```

### 🏆 Achievement System

Unlock 10 unique achievements:

- **First Steps**: Make your first contribution
- **Centurion**: Reach 100 contributions
- **Full Week**: Fill an entire week
- **Artist**: Use all 10 patterns
- **Perfectionist**: Fill all 364 squares
- **Time Traveler**: Use undo 10 times
- **Streak Master**: Achieve a 50+ streak
- **Style Icon**: Try all 3 themes
- **Archivist**: Save and load a pattern
- **Dedicated**: Make 500 total changes

---

## 🎮 Demo

### Live Preview

👉 **[Play Now](https://your-username.github.io/contribution-matrix-pro/)**

### Screenshots

<details>
<summary>📸 View Screenshots</summary>

#### Van_Dragon Theme
![Van Dragon Theme](https://via.placeholder.com/800x500/0c0c1d/00ff9d?text=Van+Dragon+Theme)

#### Draw Mode Active
![Draw Mode](https://via.placeholder.com/800x500/0c0c1d/00ff9d?text=Draw+Mode+Active)

#### Achievement Unlocked
![Achievement](https://via.placeholder.com/800x500/0c0c1d/00ff9d?text=Achievement+Unlocked)

#### Pattern Gallery
![Patterns](https://via.placeholder.com/800x500/0c0c1d/00ff9d?text=Pattern+Gallery)

</details>

---

## 🚀 Installation

### Option 1: Direct Download

1. Download `contribution-game-enhanced.html`
2. Open in any modern browser
3. Start creating!

```bash
# Clone the repository
git clone https://github.com/your-username/contribution-matrix-pro.git

# Navigate to the directory
cd contribution-matrix-pro

# Open in browser
open contribution-game-enhanced.html
```

### Option 2: GitHub Pages

1. Fork this repository
2. Enable GitHub Pages in Settings
3. Access at: `https://your-username.github.io/contribution-matrix-pro/`

### Option 3: Embed in Your Profile

Add to your GitHub profile README:

```html
<div align="center">
  <a href="https://your-username.github.io/contribution-matrix-pro/">
    <img src="https://img.shields.io/badge/Play-Contribution_Game-00ff9d?style=for-the-badge" alt="Play Game"/>
  </a>
</div>
```

---

## 📖 Usage Guide

### Getting Started

1. **Click Mode** (Default)
   - Click any cell to cycle through intensity levels (0→1→2→3→4→0)
   - Perfect for precise edits

2. **Draw Mode**
   - Press `D` or click "DRAW MODE" button
   - Select intensity from the selector
   - Click and drag to paint
   - Press `D` again or "EXIT DRAW" to return to click mode

3. **Using Patterns**
   - Click any pattern button to apply instantly
   - Combine patterns for unique designs
   - Use undo if you don't like the result

4. **Saving Your Work**
   - Press `S` or click "SAVE" button
   - Your pattern is stored in browser localStorage
   - Load anytime with `L` or "LOAD" button

5. **Exporting**
   - Click "EXPORT" button
   - PNG image downloads automatically
   - Share on social media or use in projects

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `C` | Clear all cells |
| `R` | Randomize grid |
| `F` | Fill all cells to max intensity |
| `D` | Toggle draw mode |
| `S` | Save current pattern |
| `L` | Load saved pattern |
| `Ctrl/Cmd + Z` | Undo last action |
| `Ctrl/Cmd + Y` | Redo action |

---

## 🎨 Themes

### Van_Dragon (Default)
- **Primary**: Dark space blue (#0c0c1d)
- **Accent**: Neon green (#00ff9d)
- **Vibe**: Cyberpunk, Matrix-inspired

### Dragonfire
- **Primary**: Deep purple (#1a0c1d)
- **Accent**: Hot pink (#ff3366)
- **Vibe**: Bold, energetic, passionate

### Cybervoid
- **Primary**: Deep ocean (#000814)
- **Accent**: Cyan blue (#00b4d8)
- **Vibe**: Cool, technical, professional

Switch themes using the buttons at the top of the page!

---

## 🏆 Achievements System

Track your progress and unlock achievements as you create:

```javascript
// Achievement Types
{
  milestone: "Reach contribution counts",
  creative: "Use patterns and features",
  persistence: "Total changes and undo usage",
  mastery: "Complete specific challenges"
}
```

### Achievement Tiers

- 🥉 **Bronze**: 0-3 achievements (Beginner)
- 🥈 **Silver**: 4-6 achievements (Intermediate)
- 🥇 **Gold**: 7-9 achievements (Advanced)
- 💎 **Diamond**: 10 achievements (Master)

---

## 🔧 Technical Details

### Tech Stack

- **HTML5**: Semantic structure
- **CSS3**: Custom properties, grid, flexbox, animations
- **Vanilla JavaScript**: ES6+, no frameworks
- **LocalStorage API**: Data persistence
- **Canvas API**: Image export

### Performance

- ⚡ **Lightning Fast**: Renders 364 cells instantly
- 💾 **Lightweight**: ~50KB total (uncompressed)
- 🔋 **Efficient**: Minimal CPU/memory usage
- 📱 **Responsive**: Adapts to any screen size

### Code Quality

```javascript
// Clean, modular architecture
class ContributionGame {
  // State management
  // Event handling
  // Pattern generation
  // Achievement system
  // Export functionality
}
```

### File Structure

```
contribution-matrix-pro/
│
├── contribution-game-enhanced.html  # Main game file
├── README.md                        # This file
├── LICENSE                          # MIT License
└── assets/                          # (Optional) Images, etc.
```

---

## 🌐 Browser Support

| Browser | Version | Supported |
|---------|---------|-----------|
| Chrome | 90+ | ✅ |
| Firefox | 88+ | ✅ |
| Safari | 14+ | ✅ |
| Edge | 90+ | ✅ |
| Opera | 76+ | ✅ |

**Note**: Requires a modern browser with ES6+ support.

---

## 💡 Tips & Tricks

### Creating Unique Patterns

1. **Layer Patterns**: Apply multiple patterns sequentially
2. **Partial Fills**: Use patterns then selectively clear areas
3. **Gradient Effects**: Use the gradient pattern as a base
4. **Symmetry**: Use border + cross for symmetric designs
5. **Animation Study**: Watch the animate feature for inspiration

### Best Practices

- ✓ Save frequently (it's automatic, but manual save helps for backups)
- ✓ Experiment with draw mode for organic shapes
- ✓ Use undo liberally - you have 50 states!
- ✓ Export before major changes for safety
- ✓ Try all themes to see different color effects

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Ways to Contribute

1. **Report Bugs**: Open an issue with details
2. **Suggest Features**: Share your ideas
3. **Submit PRs**: Add new patterns, themes, or features
4. **Improve Docs**: Help make this README better
5. **Share**: Star the repo and spread the word!

### Development Setup

```bash
# Fork and clone
git clone https://github.com/your-username/contribution-matrix-pro.git

# Create a branch
git checkout -b feature/amazing-feature

# Make changes and test

# Commit
git commit -m "Add amazing feature"

# Push
git push origin feature/amazing-feature

# Open a Pull Request
```

### Adding New Patterns

```javascript
// In the ContributionGame class:
createYourPattern() {
    this.clear();
    this.saveHistory();
    
    // Your pattern logic here
    for (let week = 0; week < this.weeks; week++) {
        for (let day = 0; day < this.daysPerWeek; day++) {
            // Calculate level based on your algorithm
            const level = /* your calculation */;
            
            this.grid[week][day].dataset.level = level;
            this.grid[week][day].className = 'contribution-cell';
            if (level > 0) {
                this.grid[week][day].classList.add(`active-${level}`);
            }
        }
    }
    
    this.updateStats();
    this.saveToStorage();
}
```

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Van_Dragon Codex

Permission is hereby granted, free of charge, to any person obtaining a copy...
```

---

## 🎖️ Credits

### Created By

**Van_Dragon Codex**  
- GitHub: [@your-username](https://github.com/your-username)
- Portfolio: [your-portfolio.com](https://your-portfolio.com)
- Twitter: [@yourhandle](https://twitter.com/yourhandle)

### Inspiration

- GitHub's contribution graph design
- Cyberpunk aesthetics
- Creative coding community

### Technologies

- [Font Awesome](https://fontawesome.com/) - Icons
- [Google Fonts](https://fonts.google.com/) - Orbitron & Share Tech Mono
- Modern web standards (HTML5, CSS3, ES6+)

---

## 📊 Stats

![GitHub stars](https://img.shields.io/github/stars/your-username/contribution-matrix-pro?style=social)
![GitHub forks](https://img.shields.io/github/forks/your-username/contribution-matrix-pro?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/your-username/contribution-matrix-pro?style=social)

![GitHub issues](https://img.shields.io/github/issues/your-username/contribution-matrix-pro?style=flat-square)
![GitHub pull requests](https://img.shields.io/github/issues-pr/your-username/contribution-matrix-pro?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/your-username/contribution-matrix-pro?style=flat-square)

---

## 🚀 Roadmap

### Version 3.1 (Coming Soon)
- [ ] More pattern presets (15+ total)
- [ ] Custom color picker
- [ ] Pattern sharing via URL
- [ ] Mobile touch improvements
- [ ] Daily challenges

### Version 3.2 (Future)
- [ ] Multiplayer collaborative mode
- [ ] Pattern marketplace
- [ ] Animation timeline editor
- [ ] Sound effects
- [ ] Dark/light mode toggle

### Long Term
- [ ] Integration with real GitHub contribution data
- [ ] AI-powered pattern suggestions
- [ ] Community gallery
- [ ] Progressive Web App (PWA)

---

## 💬 FAQ

<details>
<summary><b>Q: Does this connect to my real GitHub account?</b></summary>

A: No, this is a standalone creative tool. It mimics the GitHub contribution graph visually but doesn't connect to or modify your actual GitHub data.
</details>

<details>
<summary><b>Q: Where is my data stored?</b></summary>

A: All data is stored locally in your browser's localStorage. Nothing is sent to any server. Your patterns are private and stay on your device.
</details>

<details>
<summary><b>Q: Can I use this commercially?</b></summary>

A: Yes! This project is MIT licensed. You're free to use, modify, and distribute it, even commercially.
</details>

<details>
<summary><b>Q: Why aren't my achievements saving?</b></summary>

A: Make sure your browser allows localStorage. Some privacy modes or extensions might block it. Try a different browser or check your settings.
</details>

<details>
<summary><b>Q: How do I add custom patterns?</b></summary>

A: You can edit the JavaScript code and add new pattern methods. See the [Contributing](#-contributing) section for details.
</details>

<details>
<summary><b>Q: Can I change the grid size?</b></summary>

A: Currently the grid is fixed at 52 weeks × 7 days (364 cells) to match GitHub's layout. Custom grid sizes may come in a future update.
</details>

---

## 🌟 Showcase

**Made something awesome?** Share it!

Tag your creations with `#ContributionMatrixPro` on social media!

---

## 📞 Support

Need help or have questions?

- 📧 **Email**: your.email@example.com
- 💬 **Discord**: [Join our community](#)
- 🐛 **Issues**: [GitHub Issues](https://github.com/your-username/contribution-matrix-pro/issues)
- 💡 **Discussions**: [GitHub Discussions](https://github.com/your-username/contribution-matrix-pro/discussions)

---

<div align="center">

## ⭐ Star This Repo!

If you found this project useful, please consider giving it a star. It helps others discover it too!

[![Star History Chart](https://api.star-history.com/svg?repos=your-username/contribution-matrix-pro&type=Date)](https://star-history.com/#your-username/contribution-matrix-pro&Date)

---

**Made with 💚 by the Van_Dragon Codex community**

[⬆ Back to Top](#-contribution-matrix-pro)

</div>
