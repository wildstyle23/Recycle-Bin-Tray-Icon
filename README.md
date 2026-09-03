# Recycle Bin Tray Icon

![Recycle Bin Tray Icon preview](Images/Recycle%20Bin%20Tray%20Icon.png)

A lightweight [Windhawk](https://windhawk.net/) mod for Windows 11 that adds an interactive Recycle Bin icon to the system tray.

The icon follows the current Recycle Bin state, supports drag & drop, light/dark theme-aware rendering, multiple icon styles, optional auto-hide, and configurable mouse actions.

## Highlights

- Live Empty / Full Recycle Bin state
- Drag files and folders directly onto the tray icon
- System, Vector, Font, and Custom Icon rendering modes
- Light / dark theme support
- Per-monitor DPI-aware rendering
- Optional Hide when empty
- Configurable left, double, middle, and right click actions
- Native localized Recycle Bin context-menu labels
- Automatic recovery after Explorer / taskbar restart

## Installation

### Windhawk catalog

The first public release is being prepared for submission to the official Windhawk mod collection.

Once published:

1. Open **Windhawk**.
2. Go to **Explore**.
3. Search for **Recycle Bin Tray Icon**.
4. Install the mod and configure it from the Settings page.

### Manual installation

1. Install and open [Windhawk](https://windhawk.net/).
2. Click **Create Mod**.
3. Replace the template with [`recycle-bin-tray.wh.cpp`](recycle-bin-tray.wh.cpp).
4. Compile and enable the mod.

The mod runs as a Windhawk tool in a dedicated `windhawk.exe` process rather than being injected into `explorer.exe`.

## Customization

The mod provides six settings groups:

- **General**
- **Vector**
- **Font**
- **Custom Icon**
- **Actions**
- **System**

Custom icons can use `.ico`, `.png`, `.bmp`, and `.jpg` files. Transparent monochrome images can be adapted automatically to the active Light or Dark theme.

For the full feature documentation, settings details, DPI table, Font examples, drag & drop notes, and troubleshooting guide, see the embedded README inside [`recycle-bin-tray.wh.cpp`](recycle-bin-tray.wh.cpp).

## Version

Current release candidate: **1.0.0**

## License

Licensed under the **GNU General Public License Version 3 (GPL-3.0)**.
