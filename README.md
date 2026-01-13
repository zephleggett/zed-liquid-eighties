```
================================================================================
    __    _             _     __   ____  _       __    __  _
   / /   (_)___ ___  __(_)___/ /  / __/ (_)___ _/ /_  / /_(_)__  _____
  / /   / / __ `/ / / / / __  /  / /_  / / __ `/ __ \/ __/ / _ \/ ___/
 / /___/ / /_/ / /_/ / / /_/ /  / __/ / / /_/ / / / / /_/ /  __(__  )
/_____/_/\__, /\__,_/_/\__,_/  /____//_/\__, /_/ /_/\__/_/\___/____/
           /_/                         /____/

                    A Zed Editor Color Theme
                         Version 1.0.0
================================================================================
```

![Liquid Eighties Theme Screenshot](screenshot.jpg)

A warm, translucent dark theme combining macOS Tahoe's Liquid Glass aesthetic with the classic Base16 Eighties palette.

**Author:** Zeph Leggett
**License:** MIT

---

## Description

Liquid Eighties is a dark color theme for the Zed text editor featuring:

- Blurred transparency effects (Liquid Glass aesthetic)
- Safari-style chrome and tab styling
- Warm, retro-inspired UI tones
- Base16 Eighties syntax highlighting palette
- Full terminal color support
- Optimized contrast ratios for extended coding sessions

This theme was engineered for developers who appreciate the warm color temperature of vintage CRT displays combined with modern translucency effects.

---

## Color Palette

### Syntax Colors (Base16 Eighties)

| | Element | Hex |
|---|---|---|
| ![](https://img.shields.io/badge/-%20%20%20%20-1f1e1c) | Background | `#1f1e1c` |
| ![](https://img.shields.io/badge/-%20%20%20%20-d3d0c8) | Foreground | `#d3d0c8` |
| ![](https://img.shields.io/badge/-%20%20%20%20-747369) | Comments | `#747369` |
| ![](https://img.shields.io/badge/-%20%20%20%20-f2777a) | Red (tags/vars) | `#f2777a` |
| ![](https://img.shields.io/badge/-%20%20%20%20-f99157) | Orange (constants) | `#f99157` |
| ![](https://img.shields.io/badge/-%20%20%20%20-ffcc66) | Yellow (types) | `#ffcc66` |
| ![](https://img.shields.io/badge/-%20%20%20%20-99cc99) | Green (strings) | `#99cc99` |
| ![](https://img.shields.io/badge/-%20%20%20%20-66cccc) | Cyan | `#66cccc` |
| ![](https://img.shields.io/badge/-%20%20%20%20-6699cc) | Blue (functions) | `#6699cc` |
| ![](https://img.shields.io/badge/-%20%20%20%20-cc99cc) | Magenta (keywords) | `#cc99cc` |

### UI Colors

| | Element | Hex |
|---|---|---|
| ![](https://img.shields.io/badge/-%20%20%20%20-1d1c1a) | Title Bar | `#1d1c1a` |
| ![](https://img.shields.io/badge/-%20%20%20%20-4a4946) | Active Tab | `#4a4946` |
| ![](https://img.shields.io/badge/-%20%20%20%20-2d2c29) | Inactive Tab | `#2d2c29` |
| ![](https://img.shields.io/badge/-%20%20%20%20-1f1e1c) | Editor Background | `#1f1e1c` |
| | Panel Background | transparent |
| ![](https://img.shields.io/badge/-%20%20%20%20-6699cc) | Selection | `#6699cc40` |
| ![](https://img.shields.io/badge/-%20%20%20%20-6699cc) | Accent | `#6699cc` |

---

## Installation

### Method A: Zed Themes Website (Recommended)

1. Visit: https://zed-themes.com/themes/IgdISgFhi-laoQsOHG_Ns
2. Click "Install" button
3. Theme will be added to your Zed installation
4. Select "Liquid Eighties" from theme picker (`Cmd+K, Cmd+T`)

### Method B: Manual Installation

1. Locate your Zed themes directory:
   ```
   macOS:  ~/.config/zed/themes/
   Linux:  ~/.config/zed/themes/
   ```

2. Copy `liquid-eighties.json` to the themes directory:
   ```sh
   cp liquid-eighties.json ~/.config/zed/themes/
   ```

3. Restart Zed or reload configuration

4. Open Command Palette (`Cmd+Shift+P`) and select "theme selector: toggle"

5. Choose "Liquid Eighties" from the list

---

## Known Issues

- Blur effects only work on macOS with compositor enabled
- Some icon themes may not harmonize with warm color palette
- Transparency may reduce readability on very light desktop backgrounds

Report issues at: https://github.com/zephleggett/zed-liquid-eighties/issues

---

## Credits

| | |
|---|---|
| Base16 Eighties | Chris Kempson (original palette) |
| Liquid Glass | Apple Inc. (design language) |

Special thanks to the Zed team for making an excellent editor.
