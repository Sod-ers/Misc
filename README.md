
### Linux:
- Play command depends on SoX package.
- Disable show desktop shortcut in window manager/dconf.
- sudo apt install gtk-3-examples && gtk3-widget-factory
### Windows:
Registry bookmarks:

| Purpose:                         | Path:                                                                                                             |
| -------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| Run any batch script on startup. | Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Command Processor                                                  |
| Create runbox keywords.          | Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\App Paths                                   |
| Block programs from running.     | Computer\HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Microsoft\Windows NT\CurrentVersion\Image File Execution Options |
