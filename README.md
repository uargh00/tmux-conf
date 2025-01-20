# **Tmux Configuration**

### **Description**  
A custom Tmux configuration file designed to enhance productivity by enabling mouse support, optional Vim keybindings, and highlighting SSH sessions in the pane borders and titles.

---

### **Features**  
- Mouse support for scrolling and text selection.
- Optional Vim-style keybindings in copy mode.
- Pane titles show `"SSH"` for active SSH sessions.
- Subtle highlighting of active and inactive panes.
- Synchronization mode for writing in all panes at once.
- Configuration reload shortcut.

---

### **Installation**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/tmux-config.git
   ```
   
2. **Copy the Tmux configuration file to your home directory**:
   ```bash
   cp tmux-config/tmux.conf ~/.tmux.conf
   ```

3. **Reload Tmux**:
   If Tmux is already running:
   ```bash
   tmux source-file ~/.tmux.conf
   ```

---

### **Compatibility**  
This configuration is compatible with **Tmux version 3.2 and above**.

---

### **Keybindings Overview**

| Shortcut      | Description                                   |
| --------------| ----------------------------------------------|
| `Ctrl + b + S`| Toggle pane synchronization (write in all panes). |
| `Ctrl + b + r`| Reload Tmux configuration.                    |
| `Ctrl + b + %`| Split window vertically (side-by-side panes).  |
| `Ctrl + b + "`| Split window horizontally (stacked panes).     |
| `Ctrl + b + h/j/k/l` | Move between panes (like Vim navigation). |
| `Ctrl + b + H/J/K/L` | Resize panes in 5-column/row increments.  |

---

### **Customizations**  
- The configuration uses `screen-256color` to enable 256-color support.
- To enable Vim keybindings in copy mode, uncomment the following line in `~/.tmux.conf`:
  ```bash
  # setw -g mode-keys vi
  ```

---

### **Contributing**  
Feel free to fork the repository, create a branch for your changes, and open a pull request.

---
