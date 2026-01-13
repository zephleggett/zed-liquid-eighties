```
================================================================================
    __    _             _     __   ____  _       __    __  _
   / /   (_)___ ___  __(_)___/ /  / __/ (_)___ _/ /_  / /_(_)__  _____
  / /   / / __ `/ / / / / __  /  / /_  / / __ `/ __ \/ __/ / _ \/ ___/
 / /___/ / /_/ / /_/ / / /_/ /  / __/ / / /_/ / / / / /_/ /  __(__  )
/_____/_/\__, /\__,_/_/\__,_/  /_/   /_/\__, /_/ /_/\__/_/\___/____/
           /_/                         /____/

                    A Zed Editor Color Theme
                         Version 1.0.0
================================================================================
```

                         LIQUID EIGHTIES THEME
                         =====================

    "A warm, translucent dark theme combining macOS Tahoe's Liquid
     Glass aesthetic with the classic Base16 Eighties palette."

                    Author: Zeph Leggett <zephleggett>
                    License: MIT
                    Last Updated: 2026-01-12


--------------------------------------------------------------------------------
                            TABLE OF CONTENTS
--------------------------------------------------------------------------------

    1. DESCRIPTION
    2. SYSTEM REQUIREMENTS
    3. INSTALLATION
    4. COLOR PALETTE
    5. SCREENSHOTS
    6. KNOWN ISSUES
    7. CHANGELOG
    8. CREDITS
    9. CONTACT


--------------------------------------------------------------------------------
1. DESCRIPTION
--------------------------------------------------------------------------------

Liquid Eighties is a dark color theme for the Zed text editor featuring:

    * Blurred transparency effects (Liquid Glass aesthetic)
    * Safari-style chrome and tab styling
    * Warm, retro-inspired UI tones
    * Base16 Eighties syntax highlighting palette
    * Full terminal color support
    * Optimized contrast ratios for extended coding sessions

This theme was engineered for developers who appreciate the warm color
temperature of vintage CRT displays combined with modern translucency effects.


--------------------------------------------------------------------------------
2. SYSTEM REQUIREMENTS
--------------------------------------------------------------------------------

    MINIMUM:
    --------
    - Zed Editor ................... v0.150.0 or higher
    - Operating System ............. macOS 15.0+ (Tahoe) recommended
                                     Linux/Windows supported (no blur)
    - Display ...................... 1024x768 minimum
                                     1920x1080+ recommended
    - Color Depth .................. 24-bit True Color

    RECOMMENDED:
    ------------
    - macOS Tahoe with Liquid Glass enabled
    - Monitor with accurate color reproduction
    - Dark system appearance for best results

    NOTE: Blur/transparency effects require macOS with compositor support.
          On other platforms, backgrounds will render as solid colors.


--------------------------------------------------------------------------------
3. INSTALLATION
--------------------------------------------------------------------------------

    METHOD A - Zed Themes Website (Recommended)
    -------------------------------------------

    1. Visit: https://zed-themes.com/themes/IgdISgFhi-laoQsOHG_Ns
    2. Click "Install" button
    3. Theme will be added to your Zed installation
    4. Select "Liquid Eighties" from theme picker (Cmd+K, Cmd+T)


    METHOD B - Manual Installation
    ------------------------------

    1. Locate your Zed themes directory:

           macOS:  ~/.config/zed/themes/
           Linux:  ~/.config/zed/themes/

    2. Copy `liquid-eighties.json` to the themes directory:

           $ cp liquid-eighties.json ~/.config/zed/themes/

    3. Restart Zed or reload configuration

    4. Open Command Palette (Cmd+Shift+P) and select:
       "theme selector: toggle"

    5. Choose "Liquid Eighties" from the list


    METHOD C - Settings.json
    ------------------------

    Add the following to your ~/.config/zed/settings.json:

        {
          "theme": "Liquid Eighties"
        }


--------------------------------------------------------------------------------
4. COLOR PALETTE
--------------------------------------------------------------------------------

    SYNTAX COLORS (Base16 Eighties)
    ===============================

    Element             Hex Code      Sample
    ------------------  ------------  ----------------
    Background          #1f1e1c       [dark warm gray]
    Foreground          #d3d0c8       [warm cream]
    Comments            #747369       [warm gray]
    Red (tags/vars)     #f2777a       [coral red]
    Orange (constants)  #f99157       [warm orange]
    Yellow (types)      #ffcc66       [golden yellow]
    Green (strings)     #99cc99       [soft green]
    Cyan                #66cccc       [teal]
    Blue (functions)    #6699cc       [steel blue]
    Magenta (keywords)  #cc99cc       [lavender]


    UI COLORS
    =========

    Element                  Hex Code
    -----------------------  ------------
    Title Bar                #1d1c1a
    Active Tab               #4a4946
    Inactive Tab             #2d2c29
    Editor Background        #1f1e1c
    Panel Background         transparent
    Selection                #6699cc40
    Accent                   #6699cc


--------------------------------------------------------------------------------
5. SCREENSHOTS
--------------------------------------------------------------------------------

    Screenshots available at:
    https://zed-themes.com/themes/IgdISgFhi-laoQsOHG_Ns


--------------------------------------------------------------------------------
6. KNOWN ISSUES
--------------------------------------------------------------------------------

    * Blur effects only work on macOS with compositor enabled
    * Some icon themes may not harmonize with warm color palette
    * Transparency may reduce readability on very light desktop backgrounds

    Report issues at:
    https://github.com/zephleggett/liquid-eighties/issues


--------------------------------------------------------------------------------
7. CHANGELOG
--------------------------------------------------------------------------------

    v1.0.0 (2026-01-12)
    -------------------
    - Initial public release
    - Full Base16 Eighties syntax palette
    - macOS Tahoe Liquid Glass UI styling
    - Warm color temperature adjustments
    - Safari-style tab chrome
    - Complete terminal color definitions


--------------------------------------------------------------------------------
8. CREDITS
--------------------------------------------------------------------------------

    Theme Design:       Zeph Leggett
    Base16 Eighties:    Chris Kempson (original palette)
    Liquid Glass:       Apple Inc. (design language)

    Special thanks to the Zed team for making an excellent editor.


--------------------------------------------------------------------------------
9. CONTACT
--------------------------------------------------------------------------------

    Author:     Zeph Leggett
    GitHub:     https://github.com/zephleggett
    Theme URL:  https://zed-themes.com/themes/IgdISgFhi-laoQsOHG_Ns


================================================================================
    This theme is provided "AS IS" without warranty of any kind, express or
    implied. Use at your own risk. The author is not responsible for any
    eye strain, mass, or productivity loss resulting from extended use of
    this color scheme.

    Copyright (c) 2026 Zeph Leggett - MIT License
================================================================================

                            EOF - README.md
