<script setup>
import { version } from "/global.ts";
</script>

# Getting Started

This guide will help you get up and running with En Croissant.

## Installation

En Croissant is available for Windows, Linux, and macOS.

### Windows

1. Go to the [Download](/download) page.
2. Click on the **Windows** download button to get the latest `.exe` installer.
3. Run the installer and follow the on-screen instructions.

### Linux

1. Go to the [Download](/download) page.
2. Download the `.AppImage`, `.deb`, or `.rpm` file depending on your distribution.
3. For AppImage:
   - Make the file executable: `chmod +x en-croissant_{{    version }}_amd64.AppImage`
   - Run it: `./en-croissant_{{ version }}_amd64.AppImage`
4. For `.deb`:
   - Install using `dpkg` or your package manager: `sudo dpkg -i en-croissant_{{ version }}_amd64.deb`
5. For `.rpm`:
   - Install using your package manager: `sudo dnf install ./en-croissant-{{ version }}-1.x86_64.rpm`
6. For Raspberry Pi:
   - En Croissant is also available through [Pi-Apps](https://pi-apps.io/).

### macOS

1. Go to the [Download](/download) page.
2. Download the `.dmg` file.
3. Open the `.dmg` and drag the En Croissant app to your Applications folder.

## First Run

When you first launch En Croissant, the main dashboard will be displayed. Here are a few things to do to get started:

1.  **Configure Engines**: Go to the Engines page to download or add your favorite chess engines (like Stockfish).
2. **Add Reference Database**: Go to the Databases page to download a database to use as a reference for your analysis.
3.  **Explore Features**: Check out the Analysis board, play a game against the computer or start practicing tactics with puzzles.

You can also watch the following video for a walkthrough of some of the features in En Croissant:

<iframe
  src="https://www.youtube-nocookie.com/embed/vgFIbB6CGAg"
  title="En Croissant engine setup walkthrough"
  style="display: block; width: 100%; aspect-ratio: 16 / 9; border: 0"
  loading="lazy"
  referrerpolicy="strict-origin-when-cross-origin"
  allowfullscreen
></iframe>