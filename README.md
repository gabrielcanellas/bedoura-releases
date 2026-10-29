# Bedoura

Turn pixel art into bead patterns. Bedoura converts a PNG image into a pattern for Perler, Hama, Artkal and Nabbi beads, matching every pixel to the closest real bead color and telling you how many beads of each color you need.

Free for Windows 10 or later (64-bit). No account needed, and it works offline.

## Download

Get the latest version from the [Releases page](https://github.com/gabrielcanellas/bedoura-releases/releases).

1. Download the `.zip` file from the latest release.
2. Extract **the whole folder** (don't run the program from inside the zip).
3. Open `Bedoura.exe`.

There is no installer: to remove Bedoura, just delete the folder.

Windows may show a "protected your PC" warning the first time, because the program is not code-signed. If it does, click **More info** and then **Run anyway**.

## Quick start

1. **Choose the bead size** (Mini, Midi, Caps or Maxi) with the bead size button in the top bar. Beads of different sizes don't fit together, so each pattern uses one size. See [Bead sizes and brands](#bead-sizes-and-brands) below.
2. **Choose the color palette** with the palette button. A window lists the colors of the selected size, grouped by brand. Tick the brands or colors you want to use, and untick the ones you don't have: only ticked colors are used to match and suggest beads. At least one color must stay selected. If you don't change anything, Mini uses Artkal C and Midi uses Perler. Caps and Maxi use all their colors (each has a single brand).
3. **Open a PNG image** with the folder button. Use pixel art: 1 pixel in the image becomes 1 bead. Transparent pixels stay empty.
4. **Check the result.** The original is on the left and the bead version on the right. Move the cursor over a pixel to see which bead it uses, shown at the bottom of the window.
5. **Adjust colors if you want.** Click a color in the list on the right and pick another bead. Hover over an option to preview it before confirming.
6. **Pick a pegboard** (optional) with the pegboard button, if you want to see where each board starts and ends. It's available for Mini and Midi beads. The Materials panel then also shows how many boards you need.
7. **Check the Materials panel** for the beads you need, grouped by brand.
8. **Export** the pattern with the export button. Choose **PDF** for the assembly guide (in the preview you can switch between portrait and landscape, then use **Print** and choose a PDF printer such as Microsoft Print to PDF to save a file, or send it to a real printer), or **.xlsx** to get an Excel spreadsheet with one colored cell per bead and its code.

You can change the bead size or the palette after loading an image: the conversion is recalculated. If you had edited colors by hand, the program warns you first, because those edits are lost when it recalculates.

## Toolbar guide

Hover over any icon to see its name at the bottom of the window.

**Top bar, left**

| Icon | What it does |
|---|---|
| Folder | Open a PNG image |
| Export | Export the pattern as a PDF or an Excel (.xlsx) spreadsheet |

**Top bar, center**

| Icon | What it does |
|---|---|
| Palette | Choose which brands and colors are used |
| Circle with a dot | Choose the bead size (Mini, Midi, Caps, Maxi) |
| Four tiles | Choose a pegboard size, or none |
| Grid | Show or hide the grid lines |

**Top bar, right**

| Icon | What it does |
|---|---|
| Bug | Report a bug, suggest an improvement or ask a question |
| Moon / Sun | Switch between the light and the dark theme |
| Globe | Change the language (English, Português, Español) |
| Info | About, support links and check for updates |

**Left side** (appears after you load an image)

| Icon | What it does |
|---|---|
| Arrow | Select: click a bead to mark it in both images |
| Hand | Move: drag to move the image |
| Iron | Ironing Mode: mirrors the view horizontally, for the tape method |
| Fit to screen | Center the image again |

Zoom with the mouse wheel. You can also move the image at any time by holding the middle mouse button and dragging.

## Bead sizes and brands

| Size | Brands and series |
|---|---|
| Mini (2.6 mm) | Artkal A, C and M; Hama Mini; Perler Mini |
| Midi (5 mm) | Artkal R and S; Hama Midi; Nabbi; Perler Midi |
| Caps (about 10 mm) | Perler Caps |
| Maxi (about 10 mm) | Hama Maxi |

Pegboards available: Midi has 29×29 and a small 16×16 (not connectable); Mini has 29×29, 50×50 and 52×52. Caps and Maxi have no pegboard option yet.

## Features

- Color matching against a built-in palette of 1222 real bead colors (Artkal, Hama, Nabbi and Perler).
- Choose which brands and colors take part in the conversion.
- Manual color editing per color, with live preview.
- Materials summary with the number of beads per brand and color.
- Pegboard support: see where each board starts and ends, and how many boards you need.
- Ironing Mode: mirrors the view horizontally, for the tape method. The PDF export follows it.
- Grid, zoom and pan.
- Excel export (.xlsx): one cell per bead, filled with the bead color and showing its code. Pegboard divisions appear as thick borders, and Ironing Mode is followed.
- PDF export: a full pattern page plus one page per pegboard (when a pegboard is selected). Bead codes are printed in each cell for patterns up to 52×52 beads, and always on the pegboard pages. On very large patterns (above about 360 beads on the longest side) the thin grid lines are left out so the colors stay visible.
- Light and dark themes, switched with the moon/sun button in the top bar.
- Interface in English, Portuguese and Spanish.

## Good to know

- Very large or very colorful images can take several seconds to convert. The window stays responsive and a loading indicator is shown meanwhile.
- Only PNG files are supported.
- Images above 300×300 beads show a warning, and images above 1000×1000 are blocked.
- Partly transparent pixels are treated as opaque. Only fully transparent pixels stay empty.
- Colors are matched by RGB distance, so the closest bead on paper may not always be the closest to your eye. Use the manual editing to fix it.
- Updates are not installed automatically: download the new version and replace the old folder.
- Your theme, language and palette choices are not saved when you close the program (it always opens in the light theme), and projects can't be saved yet.
- Three recent Hama colors (Dusty Blue, Fuchsia Pink and Mustard) are not in the palette yet.

## Updates

Open **About** (the info icon) and click **Check for updates**. The program asks GitHub for the latest release only when you click, sends no information about you or your files, and saves nothing on your computer. If a newer version exists, you get a link to its Releases page. You can also check the [Releases page](https://github.com/gabrielcanellas/bedoura-releases/releases) at any time.

## Feedback and support

Found a bug, have an idea or a question? Use the bug icon inside the program, or fill in the [feedback form](https://forms.gle/sYnCZzWyUVS55pNG6).

Bedoura is free. If you like it and want to support the project, you can [buy me a coffee](https://ko-fi.com/gabrielcanellas). It's optional and doesn't unlock anything.

## License

Bedoura is proprietary, closed-source software, free to use for personal or commercial purposes. The patterns and PDFs you create belong to you. See [LICENSE.md](LICENSE.md) for the full terms. To share Bedoura with someone, please send them this page instead of the files.

Color data comes from the [beadcolors](https://github.com/maxcleme/beadcolors) project (MIT License). Perler, Hama, Artkal, Nabbi and other brand names are trademarks of their respective owners. Bedoura is an independent project and is not affiliated with any of these brands.

© 2026 Gabriel Canellas. All rights reserved.
