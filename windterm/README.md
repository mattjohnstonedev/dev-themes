# WindTerm Themes

A curated collection of custom visual themes for the [WindTerm](https://github.com/kingToolbox/WindTerm) terminal emulator.

## Prerequisites

- [WindTerm](https://github.com/kingToolbox/WindTerm) installed on your system.

## Installation

1. Download or clone the desired theme folder from this repository.
2. Copy the theme folder (e.g., `dracula`, `vscode-dark`) into your WindTerm themes directory:
   - **Windows:** `%USERPROFILE%\.wind\themes\`
   - **macOS/Linux:** `~/.wind/themes/`
3. Restart WindTerm if it is already running.
4. Open **Session Preferences** → **Appearance** → **Theme** and select the newly installed theme from the list.

> **Note:** Each theme folder contains `gui.theme`, `icon.theme`, and `scheme.theme` files required by WindTerm. Ensure all three files are present in the copied folder.

## Available Themes

| Theme | Preview | Files |
|-------|---------|-------|
| [Dracula](./dracula/) | ![Screenshot of Dracula](../assets/screenshots/windterm-dracula.png) | `gui.theme`, `icon.theme`, `scheme.theme` |
| [True Godot](./true-godot/) | ![Screenshot of True Godot](../assets/screenshots/windterm-true-godot.png) | `gui.theme`, `icon.theme`, `scheme.theme` |
| [VS Code Dark](./vscode-dark/) | ![Screenshot of VS Code Dark](../assets/screenshots/windterm-vscode-dark.png) | `gui.theme`, `icon.theme`, `scheme.theme` |

---

*Want to contribute a new WindTerm theme? Follow the file structure above and open a pull request.*
