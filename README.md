## ✅ Prefix Key

**Prefix = Ctrl + Space**
(You press this first before any regular tmux command — unless noted as "no prefix needed".)

---

## 🧱 Pane Management

### Split Panes (in current dir):

- `Prefix + "` → Split horizontally
- `Prefix + %` → Split vertically

### Navigate Panes (Vim-style):

- `Prefix + h` → Left
- `Prefix + j` → Down
- `Prefix + k` → Up
- `Prefix + l` → Right

### Navigate Panes (no prefix):

- `Alt + ←` → Left
- `Alt + →` → Right
- `Alt + ↑` → Up
- `Alt + ↓` → Down

### Close Pane:

- `Ctrl + d` → Closes the active pane (same as running `exit` inside it)
- _(Optional)_ `Prefix + x` → Close active pane (if bound)

---

## 🪟 Window (Tab) Management

- `Prefix + c` → New window
- `Prefix + ,` → Rename window
- `Prefix + n` → Next window
- `Prefix + p` → Previous window

### Navigate Windows (no prefix):

- `Shift + ←` → Previous window
- `Shift + →` → Next window
- `Alt + H` → Previous window
- `Alt + L` → Next window

---

## 📋 Copy Mode (vi-style)

Inside `copy-mode-vi`:

- `v` → Start selection
- `Ctrl + v` → Toggle block/rectangle selection
- `y` → Copy selection & exit

---

Keep this as a quick cheat sheet for your tmux muscle memory. Let me know if you want to add resize shortcuts, plugin commands, or session management.
