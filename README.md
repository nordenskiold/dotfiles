# Dotfiles

Personal configuration files for macOS.

## Karabiner-Elements Configuration

This repository contains my custom keyboard mappings for [Karabiner-Elements](https://karabiner-elements.pqrs.org/), a powerful keyboard customizer for macOS.

### Installation

1. Install Karabiner-Elements
2. Copy `karabiner/karabiner.json` to `~/.config/karabiner/karabiner.json`
3. Restart Karabiner-Elements

### Key Mappings

#### Windows-Style Shortcuts

These mappings provide Windows-like keyboard shortcuts on macOS:

| Shortcut | Action | Scope |
|----------|--------|-------|
| `Ctrl+C` | Copy | Global |
| `Ctrl+V` | Paste | Global |
| `Ctrl+X` | Cut | Global |
| `Ctrl+Z` | Undo | Global |
| `Ctrl+Y` | Redo | Global |
| `Ctrl+A` | Select All | Global |
| `Ctrl+F` | Find | Global |
| `Ctrl+S` | Save | Global |
| `Ctrl+N` | New Window/Document | Global |
| `Ctrl+O` | Open | Global |
| `Ctrl+P` | Print | Global |
| `Ctrl+W` | Close Window/Tab | Global |
| `Ctrl+T` | New Tab | Global |
| `Ctrl+R` | Refresh | Global |
| `Ctrl+B` | Bold | Global |
| `Ctrl+I` | Italic | Global |
| `Ctrl+U` | Underline | Global |

#### Terminal-Specific Shortcuts

| Shortcut | Action | Scope |
|----------|--------|-------|
| `Ctrl+Shift+C` | Copy | Terminal Emulators Only |
| `Ctrl+Shift+V` | Paste | Terminal Emulators Only |
| `Ctrl+Insert` | Copy | Terminal Emulators |
| `Shift+Insert` | Paste | Terminal Emulators |
| `Ctrl+/` | Comment/Uncomment | Terminal Emulators |

#### Navigation Shortcuts

| Shortcut | Action | Scope |
|----------|--------|-------|
| `Home` | Jump to beginning of line | Global |
| `End` | Jump to end of line | Global |
| `Ctrl+Home` | Jump to beginning of document | Global |
| `Ctrl+End` | Jump to end of document | Global |
| `Shift+Home` | Select to beginning of line | Global |
| `Shift+End` | Select to end of line | Global |
| `Ctrl+Shift+Home` | Select to beginning of document | Global |
| `Ctrl+Shift+End` | Select to end of document | Global |
| `Ctrl+Left` | Move cursor one word left | Global |
| `Ctrl+Right` | Move cursor one word right | Global |
| `Ctrl+Shift+Left` | Select one word left | Global |
| `Ctrl+Shift+Right` | Select one word right | Global |

#### Editing Shortcuts

| Shortcut | Action | Scope |
|----------|--------|-------|
| `Ctrl+Backspace` | Delete word backward | Global |
| `Ctrl+Delete` | Delete word forward | Global |
| `Ctrl+Enter` | Insert line below | Global |
| `Ctrl+Shift+Enter` | Insert line above | Global |
| `Ctrl+Space` | Autocomplete/Suggestions | Global |

#### Application Launchers

| Shortcut | Action | Scope |
|----------|--------|-------|
| `Cmd+1` | Open Finder | Global |
| `Cmd+2` | Open first pinned Dock app | Global |
| `Cmd+3` | Open second pinned Dock app | Global |
| `Cmd+4` | Open third pinned Dock app | Global |
| `Cmd+5` | Open fourth pinned Dock app | Global |
| `Cmd+6` | Open fifth pinned Dock app | Global |
| `Cmd+7` | Open sixth pinned Dock app | Global |
| `Cmd+8` | Open eighth pinned Dock app | Global |
| `Cmd+9` | Open ninth pinned Dock app | Global |

#### System Shortcuts

| Shortcut | Action | Scope |
|----------|--------|-------|
| `Win+L` | Lock Screen | Login Window |
| `Alt+Ctrl+L` | Lock Screen | Global |
| `F1` | Brightness Down | Global |
| `F3` | Mission Control | Global |
| `Alt+F4` | Close Window | Terminal Emulators |
| `Ctrl+F4` | Close Tab | Chrome Only |

#### Mouse Shortcuts

| Shortcut | Action | Scope |
|----------|--------|-------|
| `Mouse3` | Toggle Mission Control | Global |
| `Mouse6` | Toggle Mission Control | Global |
| `Ctrl+Mouse4` | Switch to left virtual desktop | Global |
| `Ctrl+Mouse5` | Switch to right virtual desktop | Global |
| `Ctrl+Mouse1` (VSCode) | Swapped with `Alt+Mouse1` | VSCode Only |
| `Mouse3` (VSCode) | Toggle Bookmark (swapped with `Alt+Cmd+K`) | VSCode Only |

#### Application-Specific Behavior

| Configuration | Description | Scope |
|--------------|-------------|-------|
| Terminal Ctrl→Cmd | Changes `Ctrl` to `Cmd` for Terminal app | Terminal Only |
| Browser Tab Switching | Changes `Cmd+Tab` to `Ctrl+Tab` | Browsers Only |
| Alt Tab | Changes `Cmd+Tab` to `Option+Tab` | Global |

### Excluded Applications

The following applications are excluded from certain key remappings to preserve their native shortcuts:

- Virtual Machines (VirtualBox, Parallels, VMware Fusion)
- Emacs
- JetBrains IDEs
- Sublime Text
- Citrix XenApp
- Microsoft Remote Desktop
- Chrome Remote Desktop

## License

Feel free to use and modify these configurations for your own needs.
