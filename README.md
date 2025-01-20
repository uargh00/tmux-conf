# **Tmux Configuration**

![Status](https://img.shields.io/badge/status-active-brightgreen)  
![Tmux Version](https://img.shields.io/badge/Tmux-3.2%2B-blue)

## **Overview**  
A custom Tmux configuration file designed to enhance productivity with features like mouse support, optional Vim keybindings, and SSH session highlighting.

## **Features**
- Mouse support for scrolling and text selection.
- Optional Vim-style keybindings in copy mode.
- Pane titles display `"SSH"` for active SSH sessions.
- Subtle highlighting of active and inactive panes.
- Pane synchronization mode.
- Configuration reload shortcut.

## **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/username/tmux-config.git
   ```

2. Copy the Tmux configuration file to your home directory:
   ```bash
   cp tmux-config/tmux.conf ~/.tmux.conf
   ```

3. Reload Tmux if it's already running:
   ```bash
   tmux source-file ~/.tmux.conf
   ```

## **Compatibility**  
This configuration is compatible with **Tmux version 3.2 and above**.

## **Keybindings**

| Shortcut        | Description                                       |
|------------------|---------------------------------------------------|
| `Ctrl + b + S`  | Toggle pane synchronization (write in all panes). |
| `Ctrl + b + r`  | Reload Tmux configuration.                        |
| `Ctrl + b + %`  | Split window vertically (side-by-side panes).      |
| `Ctrl + b + "`  | Split window horizontally (stacked panes).         |
| `Ctrl + b + h/j/k/l` | Move between panes (like Vim navigation).     |
| `Ctrl + b + H/J/K/L` | Resize panes in 5-column/row increments.      |

## **Customizations**
To enable Vim keybindings in copy mode, uncomment the following line in `~/.tmux.conf`:
```bash
# setw -g mode-keys vi
```

## **Contributing**
Contributions are welcome! Feel free to fork the repository, create a branch, and open a pull request.
