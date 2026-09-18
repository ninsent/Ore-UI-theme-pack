<!--
SPDX-FileCopyrightText: 2026 Nursultan Akim

SPDX-License-Identifier: CC0-1.0
-->

Ore UI - Font (Monocraft)
---
The pixel font used by every Ore UI theme in this pack. All themes set `font-family: "Monocraft"` in their stylesheet, so install this font first to get the intended look. If it is missing, Prism Launcher falls back to your system monospace font.

Monocraft is a monospaced programming font inspired by the Minecraft typeface, made by [Idrees Hassan](https://github.com/IdreesInc/Monocraft). This folder bundles version 4.2 unchanged.

## Contents
```
Ore UI - Font (Monocraft)/
├── Monocraft.ttf              Regular weight (the one the themes use)
├── weights/                   Optional extra weights and italics
│   ├── Monocraft-ExtraLight.ttf
│   ├── Monocraft-ExtraLight-Italic.ttf
│   ├── Monocraft-Light.ttf
│   ├── Monocraft-Light-Italic.ttf
│   ├── Monocraft-Italic.ttf
│   ├── Monocraft-SemiBold.ttf
│   ├── Monocraft-SemiBold-Italic.ttf
│   ├── Monocraft-Bold.ttf
│   ├── Monocraft-Bold-Italic.ttf
│   ├── Monocraft-Black.ttf
│   └── Monocraft-Black-Italic.ttf
├── LICENSE                    SIL Open Font License 1.1
└── README.md
```

Only `Monocraft.ttf` is required. The files in `weights/` share the same family name, so installing them lets bold or italic text in the launcher render with real Monocraft glyphs instead of synthesized ones.

## Installation

### Windows
1. Select `Monocraft.ttf` (and any files from `weights/` you want).
2. Right-click and choose **Install** (or **Install for all users**).

### macOS
1. Double-click `Monocraft.ttf` to open it in Font Book.
2. Click **Install**. Repeat for any files from `weights/`.

### Linux
1. Copy the `.ttf` files into `~/.local/share/fonts/` (create the folder if needed).
2. Run `fc-cache -f` to refresh the font cache.

Restart Prism Launcher after installing so the new font is picked up.

## Using a different weight
The themes reference the family name `Monocraft`, which resolves to the Regular weight. To use another weight everywhere, edit the rule at the top of a theme's `themeStyle.css`, for example:

```css
* {
    font-family: "Monocraft", monospace;
    font-weight: 300; /* Light */
}
```

## License
Monocraft is distributed under the SIL Open Font License, Version 1.1. The full text is in the `LICENSE` file in this folder.

```
Copyright (c) 2022, Idrees Hassan (https://github.com/IdreesInc/Monocraft)

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is also available with a FAQ at: http://scripts.sil.org/OFL
```

The font may be bundled and redistributed with software as long as this copyright notice and the license accompany it. It may not be sold on its own.
