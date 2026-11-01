
# GrandMA3 Colour Packs ┃ Burrows Production

A collection of 64 colour themes that I made for the GrandMA3 lighting console. Got some moody dark ones for low light situations, some lighter pastel themes and a little inbetween.

Made by **Shay Burrows / [Burrows Production](https://www.instagram.com/burrows.prod/)**

![Palette Pack Preview](previews/Preview.png)

---

## Contents

- [Theme Packs](#theme-packs)
- [Installation](#installation)
- [Switching Themes](#switching-themes)
- [Resetting To Default](#resetting-to-default)
- [Compatibility](#compatibility)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

---

## Theme Packs

| Pack | Themes | Style | Preview |
|---|---|---|---|
| **Palette** | 16 | Most of the themes you'll find in an IDE (fully accented) | [View](previews/Palette_Pack_Preview.png) |
| **Rainbow** | 7 | Seven colours of the rainbow | [View](previews/Rainbow_Pack_Preview.png) |
| **Pastel** | 7 | Seven colours of the rainbow, but pastel! **Could be hard to read if colourblind** | [View](previews/Pastel_Rainbow_Preview.png) |
| **Combo** | 10 | Two-colour pairings | [View](previews/Combo_Pack_Preview.png) |
| **Pride** | 9 | Pride flag themes | [View](previews/Pride_Pack_Preview.png) |
| **Season** | 8 | Seasonal and holiday themes | [View](previews/Seasonal_Pack_Preview.png) |
| **LowLight** | 4 | Best for low light environments | [View](previews/Low_Light_Pack_Preview.png) |
| **Accessibility** | 4 | High-contrast and colour-blind-safe | [View](previews/Accessibility_Preview.png) |
| **Burrows** | 4 | My personal themes :)) | [View](previews/Burrows_Pack_Preview.png) |

---

## Installation

### 1. Download

Grab whichever colour pack you want or the combined master pack from the [Releases](../../releases) page or you can download as a ZIP (**Code -> Download ZIP**)

### 2. Copy the `.xml` files into the colour themes folder

**grandMA3 onPC: Windows**
```
C:\ProgramData\MALightingTechnology\gma3_library\colorthemes
```

`ProgramData` will be hidden by default, you can either go into file explorer and enable seeing hidden items or paste the path directly to your file explorer address bar.

**grandMA3 onPC: macOS**
```
~/MALightingTechnology/gma3_library/colorthemes
```
In Finder, press **Cmd + Shift + G** and paste the path.

**Console (via USB)**
```
grandMA3/gma3_library/colorthemes
```
Copy the files into this folder on a USB stick and plug it into the console.

If the `colorthemes` folder doesn't exist, create it with that exact name.

### 3. Import in grandMA3

1. Press **Menu** → **Desk Lights & Color Theme**
2. Tap **Active Color Theme**
3. Select the drive in the title bar (**Internal** or your USB stick)
4. Pick a theme and tap **Import**

---

## Switching themes

From the command line:

```
Import ColorTheme Library "Palette_01_Dracula.xml" At ColorTheme /NoConfirmation
```
> Tip: You can store the above code as a macro with regular themes so you can easily swap between em. So if house lights go down, you can swap over to a low light theme.

---

## Resetting to default

Press **MA + MA + Clear** to restore the default colour theme with factory values.

---

## Compatibility

- Built from the grandMA3 **v2.5.1** default theme structure (`DataVersion="2.5.1.1"`)
- Should work on v2.x software. Older versions may report missing or unmatched colours, which the Color Theme Compare tool can merge.
- Tested on: `2.5.1.1`

Found a window where text is hard to read? [Open an issue](../../issues) with the theme name and a screenshot.

---

## Contributing

Ideas, fixes and new palettes are always welcome :))

1. Fork the repo
2. Start from an exported grandMA3 default theme (**Desk Lights & Color Theme → Edit → Export As...**) so names and structure stay correct
3. Name files `Pack_NN_ThemeName.xml`
4. Add a credit comment under the XML declaration:
   ```xml
   <!--
     Theme Name - grandMA3 colour theme
     Author: Your Name
   -->
   ```
5. Open a pull request with a screenshot from onPC or a console

---

## Credits

**Themes by Shay Burrows / Burrows Production**

[Instagram](https://www.instagram.com/burrows.prod/) ~ [Reddit](https://www.reddit.com/user/Burrows_Production/) ~ [LinkedIn](https://www.linkedin.com/in/shay-burrows/)

Some palettes are based on open-source colour schemes:
[Dracula](https://draculatheme.com) ·
[Nord](https://www.nordtheme.com) ·
[Solarized](https://ethanschoonover.com/solarized/) ·
[Gruvbox](https://github.com/morhetz/gruvbox) ·
Monokai (Wimer Hazenberg) ·
[Tokyo Night](https://github.com/enkia/tokyo-night-vscode-theme) ·
[Catppuccin](https://catppuccin.com) ·
Okabe-Ito colour-blind-safe palette (Masataka Okabe & Kei Ito)

grandMA3 is a trademark of MA Lighting Technology GmbH. This project is not affiliated with or endorsed by MA Lighting.

---

## License
MIT License

Copyright (c) 2026 Shay Burrows

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
