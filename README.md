# Terminator-VimBinds
A configuration file for Terminator including Vim-like navigation keybindings

**Installation**

1. Clone this repo, or simply download the ./config file directly
2. Copy the **[keybindings]** section 
3. Paste it inside your own config file located in *~/.config/terminator/config*, optionally keeping your own keybindings
4. Reload Terminator
5. Done!

**Keybindings**

- Closing:
  - Close current terminal: Ctrl + W
  - Close current window: Ctrl + Q
- Copying/Pasting
  - Copy: Ctrl + Alt + C
  - Paste: Ctrl + Alt + V
- Navigation: 
  - Next Terminal: Ctrl + Tab
  - Previous Terminal: Ctrl + Shift + Tab
  - Terminal Left/Down/Up/Riht: Alt + H/J/K/L
  - Switch to Terminal 1-9: Alt + 1-9
  - Open New Tab: Ctrl + T
  - Next Tab: Ctrl + L
  - Previous Tab: Ctrl + H
  - Move Current Tab Left: Ctrl + Shift + H
  - Move Current Tab Right: Ctrl + Shift + L
  - Switch to Tab 1-9: Ctrl + 1-9
  - Move 1 Line Up: Super(win) + K
  - Move 1 Like Down: Super(win) + J
- Splitting: 
  - Split vertically: Ctrl + Alt + E
  - Split Horizontally: Ctrl + Alt + O
- Open Layout Launcher: Shift + Tilde

**NOTE**: I had to rebind the `Open Layout Launcher` action to something arbitrary because it previously used one of the above desired shortcuts. Feel free to rebind it.
