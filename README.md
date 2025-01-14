# **Tmux Configuration**

## **Overview**

This Tmux configuration enhances productivity by adding mouse support, custom keybindings, and clear visual feedback for active and inactive panes.

---

## **Key Features**

- **Mouse support:** Scroll and select/copy text using the mouse  
- **Optional Vim-like keybindings:** Navigate in copy mode like in Vim (disabled by default)  
- **Pane and window numbering from 1:** Intuitive numbering for easier navigation  
- **Subtle pane border highlighting:** Clear distinction between active and inactive panes  
- **Expanded scrollback buffer:** Store up to 10,000 lines of scroll history per pane  
- **Convenient pane management shortcuts:** Easily resize and switch between panes  

---

## **Setup Instructions**

1. Copy the `tmux.conf` file to your home directory:
   ```bash
   cp tmux.conf ~/.tmux.conf
   ```
2. To apply the configuration for all users (optional):
   ```bash
   sudo cp tmux.conf /etc/tmux.conf
   ```

---

## **Optional Configuration**

### **Enable Vim-like Keybindings**

Uncomment the following line in `~/.tmux.conf` to enable Vim-style navigation:
```bash
# setw -g mode-keys vi
```

---

## **Customization Options**

- **Mouse support:** Toggle with `set -g mouse on/off`  
- **Scrollback buffer size:** Adjust with `set -g history-limit <lines>`  
- **Pane border colors:** Modify `pane-border-style` and `pane-active-border-style`  

---
