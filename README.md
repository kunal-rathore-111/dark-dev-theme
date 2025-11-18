# 🌙 Kunal Dark Dev Theme

A sleek, high-contrast dark theme for Visual Studio Code designed for developers who code for hours. Experience vibrant syntax highlighting with carefully crafted colors that reduce eye strain and enhance code readability.

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/KunalRathore.kunal-dark-dev-theme?style=for-the-badge&label=VS%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=KunalRathore.kunal-dark-dev-theme)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/KunalRathore.kunal-dark-dev-theme?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=KunalRathore.kunal-dark-dev-theme)
[![Rating](https://img.shields.io/visual-studio-marketplace/r/KunalRathore.kunal-dark-dev-theme?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=KunalRathore.kunal-dark-dev-theme)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/kunal-rathore-111/dark-dev-theme)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](https://github.com/kunal-rathore-111/dark-dev-theme/blob/main/LICENSE)

[Preview in vscode.dev](https://vscode.dev/theme/KunalRathore.kunal-dark-dev-theme)

---

## 📸 Screenshots

![Theme Preview](./theme.png)

*Kunal Dark Dev Theme - UI Overview*

![Code Demo](./demo.png)

*Vibrant syntax highlighting in action*

---

## ✨ Features

### 🎨 Carefully Crafted Color Palette
- **Deep Dark Backgrounds**: Pure black (`#000000`) and dark blue (`#040616`) for reduced eye strain
- **Crisp White Text**: Maximum contrast with `#FFFFFF` foreground for excellent readability
- **Vibrant Accents**: 
  - 💖 **Pink** (`#f90086`) for keywords and control flow
  - 💠 **Cyan** (`#54d4ff`, `#00e5ff`) for functions, methods, and variables
  - ⚡ **Yellow** (`#FFF900`) for strings, numbers, and constants
  - 💜 **Purple** (`#7a6deef4`) for classes, types, and interfaces

### 🚀 Developer-Focused Design
- ✅ **High Contrast UI** — Optimized for long coding sessions without eye fatigue
- ✅ **Vibrant Syntax Highlighting** — Every token type has a distinct, meaningful color
- ✅ **Semantic Highlighting Ready** — Full support for VS Code's semantic token coloring
- ✅ **Multi-Language Support** — Tested and optimized for popular languages
- ✅ **Cohesive Workbench** — UI elements designed to complement your code

### 🎯 Enhanced Readability
- **Consistent Color Logic** — Similar syntax elements share color families across languages
- **Clear Visual Hierarchy** — Important code stands out naturally
- **Minimal Distractions** — UI elements fade into the background, letting your code shine

---

## 🎨 Color Palette Reference

| Element | Color | Hex Code |
|---------|-------|----------|
| Background (Primary) | ![#000000](https://via.placeholder.com/15/000000/000000?text=+) | `#000000` |
| Background (Secondary) | ![#040616](https://via.placeholder.com/15/040616/040616?text=+) | `#040616` |
| Foreground | ![#FFFFFF](https://via.placeholder.com/15/FFFFFF/FFFFFF?text=+) | `#FFFFFF` |
| Pink Accent | ![#f90086](https://via.placeholder.com/15/f90086/f90086?text=+) | `#f90086` |
| Cyan Accent | ![#54d4ff](https://via.placeholder.com/15/54d4ff/54d4ff?text=+) | `#54d4ff` |
| Bright Cyan | ![#00e5ff](https://via.placeholder.com/15/00e5ff/00e5ff?text=+) | `#00e5ff` |
| Yellow Accent | ![#FFF900](https://via.placeholder.com/15/FFF900/FFF900?text=+) | `#FFF900` |
| Purple Accent | ![#7a6dee](https://via.placeholder.com/15/7a6dee/7a6dee?text=+) | `#7a6deef4` |

---

## 📦 Installation

### Method 1: VS Code Marketplace (Recommended)

1. Open **Extensions** sidebar in VS Code (`Ctrl+Shift+X` / `Cmd+Shift+X`)
2. Search for **"Kunal Dark Dev Theme"**
3. Click **Install**
4. Click **Reload** to apply the theme
5. Go to: **File > Preferences > Color Theme** (`Ctrl+K Ctrl+T` / `Cmd+K Cmd+T`)
6. Select **"Kunal Dark Dev"** from the list

### Method 2: Quick Install via Command

Launch VS Code Quick Open (`Ctrl+P` / `Cmd+P`), paste the following command, and press enter:

```
ext install KunalRathore.kunal-dark-dev-theme
```

### Method 3: Manual Installation (from VSIX)

1. Download the latest `.vsix` file from [Releases](https://github.com/kunal-rathore-111/dark-dev-theme/releases)
2. Open VS Code
3. Go to **Extensions** sidebar
4. Click the `...` menu (top-right)
5. Select **Install from VSIX...**
6. Choose the downloaded `.vsix` file

---

## 🔧 Customization

Want to tweak the theme? You can override colors in your `settings.json`:

### Custom Workbench Colors

```json
{
  "workbench.colorCustomizations": {
    "[Kunal Dark Dev]": {
      "editor.background": "#05070B",
      "sideBar.background": "#000000",
      "activityBar.background": "#000000"
    }
  }
}
```

### Custom Token Colors

```json
{
  "editor.tokenColorCustomizations": {
    "[Kunal Dark Dev]": {
      "textMateRules": [
        {
          "scope": ["comment"],
          "settings": {
            "fontStyle": "italic"
          }
        }
      ]
    }
  }
}
```

### Enable Semantic Highlighting

For enhanced syntax coloring (recommended):

```json
{
  "editor.semanticHighlighting.enabled": true
}
```

---

## 📝 Recommended VS Code Settings

For the best experience with Kunal Dark Dev Theme:

```json
{
  "editor.fontSize": 14,
  "editor.lineHeight": 22,
  "editor.fontFamily": "JetBrains Mono, Fira Code, Consolas, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.semanticHighlighting.enabled": true,
  "editor.bracketPairColorization.enabled": true,
  "workbench.iconTheme": "material-icon-theme"
}
```

### Recommended Font

**JetBrains Mono** - A free, open-source font designed for developers  
Download: [https://www.jetbrains.com/lp/mono/](https://www.jetbrains.com/lp/mono/)

---

## 🎯 Language Support

Optimized syntax highlighting for:

### Web Development
- JavaScript & TypeScript
- React, Vue, Angular, Svelte
- HTML, CSS, SCSS, SASS, LESS
- JSX, TSX

### Backend & Systems
- Python
- PHP
- Java
- Go
- Rust
- C / C++
- C#
- Ruby
- Elixir

### Data & Config
- JSON, JSONC
- YAML
- XML
- TOML
- Markdown

### And Many More!
The theme is designed to work beautifully with any language supported by VS Code.

---

## 🐍 Python & Pylance Users

For Python developers using the Pylance extension, you can customize semantic highlighting:

```json
{
  "editor.semanticTokenColorCustomizations": {
    "[Kunal Dark Dev]": {
      "enabled": true,
      "rules": {
        "class:python": "#7a6deef4",
        "function:python": "#54d4ff",
        "parameter:python": "#FFFFFF",
        "variable:python": "#00e5ff",
        "*.decorator:python": "#f90086",
        "*.typeHint:python": "#7a6deef4"
      }
    }
  }
}
```

---

## 🤝 Contributing

Your feedback and contributions are welcome! Here's how you can help:

- 🐛 **Report Bugs**: [Open an issue](https://github.com/kunal-rathore-111/dark-dev-theme/issues)
- 💡 **Request Features**: [Suggest enhancements](https://github.com/kunal-rathore-111/dark-dev-theme/issues)
- 🔧 **Submit PRs**: Fork the repo and submit a pull request
- ⭐ **Star the Repo**: Show your support on [GitHub](https://github.com/kunal-rathore-111/dark-dev-theme)

### Development

1. Clone the repository
   ```bash
   git clone https://github.com/kunal-rathore-111/dark-dev-theme.git
   cd dark-dev-theme
   ```

2. Make your changes to the theme files

3. Test locally by pressing `F5` in VS Code to launch the Extension Development Host

4. Submit a pull request

---

## 📜 Changelog

See [CHANGELOG.md](./CHANGELOG.md) for a detailed list of changes.

---

## 📄 License

This project is licensed under the **MIT License**. See [LICENSE](./LICENSE) for details.

---

## 🔗 Links

- 🏠 [GitHub Repository](https://github.com/kunal-rathore-111/dark-dev-theme)
- 📦 [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=KunalRathore.kunal-dark-dev-theme)
- 📝 [Changelog](./CHANGELOG.md)
- 💬 [Issues & Feedback](https://github.com/kunal-rathore-111/dark-dev-theme/issues)
- 👤 [Author: Kunal Rathore](https://github.com/kunal-rathore-111)
- 📧 [Support Email](mailto:kunalworkspace111@gmail.com)

---

## 💖 Support

If you enjoy using Kunal Dark Dev Theme, consider:

- ⭐ Starring the [GitHub repository](https://github.com/kunal-rathore-111/dark-dev-theme)
- ✍️ Writing a review on the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=KunalRathore.kunal-dark-dev-theme)
- 📢 Sharing it with fellow developers
- 📧 Reach out for support: [kunalworkspace111@gmail.com](mailto:kunalworkspace111@gmail.com)

---

<div align="center">

**Enjoy coding with Kunal Dark Dev Theme!** 🌙✨

Made with ❤️ by [Kunal Rathore](https://github.com/kunal-rathore-111)

</div>
