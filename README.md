# cursor_setup_and_update.sh

Automated setup and update script for Cursor IDE on Ubuntu/Debian-based Linux systems. This script downloads the latest Cursor AppImage, sets up desktop integration, and creates a convenient launcher. It handles icon setup, desktop entry creation, and launcher script

## Features:

Downloads and installs the latest Cursor AppImage
Sets up desktop integration (icon and .desktop file)
Creates a launcher script with argument support
Updates desktop database and icon cache
Quick Install (Please review the script before running):

```bash
curl -sSL "https://raw.githubusercontent.com/day253/cursor_setup_and_update.sh/refs/heads/master/cursor_setup_and_update.sh" | bash
```

## Usage:

Save this script as 'cursor_setup_and_update.sh'
Make it executable: `chmod +x cursor_setup_and_update.sh`
Run it: `./cursor_setup_and_update.sh`
After installation, launch Cursor with: cursor [file_or_directory]

Note: This script is designed for Ubuntu/Debian-based systems and may need modifications for other distributions.
