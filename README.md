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

## Screenshot

![Liquid Eighties Theme Screenshot](screenshot.jpg)

See more at [zed-themes.com](https://zed-themes.com/themes/IgdISgFhi-laoQsOHG_Ns)

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

## Color Palette

### Syntax Colors (Base16 Eighties)

| Color | Element | Hex |
|:---:|---|---|
| ![#1f1e1c](https://via.placeholder.com/24/1f1e1c/1f1e1c.png) | Background | `#1f1e1c` |
| ![#d3d0c8](https://via.placeholder.com/24/d3d0c8/d3d0c8.png) | Foreground | `#d3d0c8` |
| ![#747369](https://via.placeholder.com/24/747369/747369.png) | Comments | `#747369` |
| ![#f2777a](https://via.placeholder.com/24/f2777a/f2777a.png) | Red (tags/vars) | `#f2777a` |
| ![#f99157](https://via.placeholder.com/24/f99157/f99157.png) | Orange (constants) | `#f99157` |
| ![#ffcc66](https://via.placeholder.com/24/ffcc66/ffcc66.png) | Yellow (types) | `#ffcc66` |
| ![#99cc99](https://via.placeholder.com/24/99cc99/99cc99.png) | Green (strings) | `#99cc99` |
| ![#66cccc](https://via.placeholder.com/24/66cccc/66cccc.png) | Cyan | `#66cccc` |
| ![#6699cc](https://via.placeholder.com/24/6699cc/6699cc.png) | Blue (functions) | `#6699cc` |
| ![#cc99cc](https://via.placeholder.com/24/cc99cc/cc99cc.png) | Magenta (keywords) | `#cc99cc` |

### UI Colors

| Color | Element | Hex |
|:---:|---|---|
| ![#1d1c1a](https://via.placeholder.com/24/1d1c1a/1d1c1a.png) | Title Bar | `#1d1c1a` |
| ![#4a4946](https://via.placeholder.com/24/4a4946/4a4946.png) | Active Tab | `#4a4946` |
| ![#2d2c29](https://via.placeholder.com/24/2d2c29/2d2c29.png) | Inactive Tab | `#2d2c29` |
| ![#1f1e1c](https://via.placeholder.com/24/1f1e1c/1f1e1c.png) | Editor Background | `#1f1e1c` |
| | Panel Background | transparent |
| ![#6699cc](https://via.placeholder.com/24/6699cc/6699cc.png) | Selection | `#6699cc40` |
| ![#6699cc](https://via.placeholder.com/24/6699cc/6699cc.png) | Accent | `#6699cc` |

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
