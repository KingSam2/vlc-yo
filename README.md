# APOI Media Player

APOI Media Player is a modern, rebranded fork of the legendary VLC media player. It combines the robust, play-anything core of VLC with a refreshed, dark-themed user interface designed for a seamless media consumption experience.

## ✨ Key Features

*   **Modern UI:** A sleek, dark-themed interface with a persistent sidebar for easy navigation.
*   **Up Next Queue:** A new visual queue directly in the player view to see what's playing next at a glance.
*   **Overlay Controls:** Refined playback controls that overlay the video content for an immersive viewing experience.
*   **Universal Playback:** Inherits VLC's ability to play almost any media file format, codec, or stream.
*   **APOI Branding:** Fully rebranded experience, from the installer to the application executable (`apoi.exe`).

## 🛠️ Building

APOI is built using the same robust build system as VLC.

### Requirements

*   **Compiler:** GCC or Clang
*   **Build System:** Autotools (autoconf, automake, libtool) or Meson
*   **Dependencies:** Standard VLC dependencies (Qt 6 for the GUI, ffmpeg, etc.)

### Basic Build Steps

1.  **Bootstrap:**
    ```bash
    ./bootstrap
    ```

2.  **Configure:**
    ```bash
    ./configure
    ```

3.  **Build:**
    ```bash
    make
    ```

## 📦 Installation

Downloads for Windows are distributed as an NSIS installer. After installation, look for **APOI Media Player** in your Start menu.

## 🤝 Credits

APOI is based on the [VLC media player](https://www.videolan.org/vlc/) by the VideoLAN project. We extend our gratitude to the thousands of contributors who have built the foundation of open-source multimedia.

---
*Based on VLC 4.0.0-dev*
