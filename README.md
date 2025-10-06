# MUVideoPlayer - Installation Guide

## Overview

MUVideoPlayer is a MuseScore plugin that synchronizes video playback with your musical scores. Follow the instructions below for your operating system.

---

## Installation Instructions

### 1. Download

Download the latest release for your operating system:
- **macOS**: `MUVideoPlayer-x.x.x-macOS.zip`
- **Windows**: `MUVideoPlayer-x.x.x-Windows.zip`
- **Linux**: `MUVideoPlayer-x.x.x-Linux.zip`

### 2. Extract the Archive

Extract the downloaded `.zip` file to access the installation files.

---

## Platform-Specific Installation

### macOS

1. Locate the extracted file `MUVideoPlayer-x.x.x.pkg`
2. Double-click the `.pkg` file to launch the installer
3. Follow the on-screen instructions to complete the installation
4. The plugin will be automatically installed to `~/Documents/MuseScore4/Plugins/MUVideoPlayer/`

### Windows

1. Locate the extracted file `MUVideoPlayer-x.x.x-Setup.exe`
2. Double-click the `.exe` file to launch the installer
3. Follow the on-screen instructions to complete the installation
4. The plugin will be automatically installed to `Documents\MuseScore4\Plugins\MUVideoPlayer\`

### Linux

1. Extract the `MUVideoPlayer-x.x.x-Linux.zip` archive
2. Copy the `MUVideoPlayer` folder to your MuseScore plugins directory:
   ```bash
   cp -r MUVideoPlayer ~/Documents/MuseScore4/Plugins/
   ```
3. Ensure the binary has execution permissions:
   ```bash
   chmod +x ~/Documents/MuseScore4/Plugins/MUVideoPlayer/dist/MUVideoPlayer
   ```

---

## Enabling the Plugin in MuseScore

1. Launch **MuseScore 4**
2. Navigate to **Plugins → Manage Plugins**
3. In the plugin manager, locate **MUVideoPlayer** in the list
4. Click **Enable** button to enable it

---

## Using MUVideoPlayer

1. Open a score in MuseScore
2. Navigate to **Plugins → MUVideoPlayer** to launch the plugin
3. When the plugin opens, select the video file you want to load
4. The video will now synchronize with your score playback

---

## Requirements

- **MuseScore 4** or later
- **macOS**: macOS 10.13 or later
- **Windows**: Windows 10 or later
- **Linux**: Ubuntu 22.04+ / Debian 11+ or compatible distribution

---

## Support

For issues or questions, please use Issues menu in this repository.

If you’d like to support my work, you can make a donation via PayPal:

[Donate via PayPal](https://www.paypal.com/donate?business=sfer.online%40free.fr&currency_code=EUR)
