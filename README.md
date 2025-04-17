# 📝 Vim Command Cheat Sheet

## 🎬 Getting Started

| Command | Description |
|---------|-------------|
| `vim <file>` | Open a file with Vim. |
| `i` | Enter **Insert** mode to start typing. |
| `ESC` | Exit **Insert** mode and return to **Normal** mode. |
| `:w` | Save (write) changes. |
| `:q` | Quit Vim. |
| `:wq` | Save and quit. |
| `:q!` | Quit without saving changes. |

---

## 🔎 Navigation

| Command | Description |
|---------|-------------|
| `h` | Move left by one character. |
| `j` | Move down by one line. |
| `k` | Move up by one line. |
| `l` | Move right by one character. |
| `w` | Move to the start of the next word. |
| `b` | Move to the beginning of the previous word. |
| `0` | Move to the beginning of the current line. |
| `$` | Move to the end of the current line. |
| `gg` | Go to the beginning of the file. |
| `G` | Go to the end of the file. |
| `H` | Move to the top of the screen. |
| `M` | Move to the middle of the screen. |
| `L` | Move to the bottom of the screen. |
| `Ctrl + f` | Scroll down one page. |
| `Ctrl + b` | Scroll up one page. |

---

## 📝 Editing Text

| Command | Description |
|---------|-------------|
| `i` | Insert before the cursor. |
| `I` | Insert at the beginning of the line. |
| `a` | Append after the cursor. |
| `A` | Append at the end of the line. |
| `o` | Open a new line below the current one. |
| `O` | Open a new line above the current one. |
| `x` | Delete the character under the cursor. |
| `dw` | Delete the current word. |
| `dd` | Delete the current line. |
| `D` | Delete from cursor to the end of the line. |
| `yy` | Yank (copy) the current line. |
| `p` | Paste after the cursor. |
| `P` | Paste before the cursor. |
| `u` | Undo last action. |
| `Ctrl + r` | Redo last undone action. |
| `.` | Repeat the last command. |

---

## 🔄 Search & Replace

| Command | Description |
|---------|-------------|
| `/search_term` | Search forward for `search_term`. |
| `?search_term` | Search backward for `search_term`. |
| `n` | Move to the next occurrence of the search term. |
| `N` | Move to the previous occurrence of the search term. |
| `:%s/old/new/g` | Replace all occurrences of `old` with `new` in the entire file. |
| `:s/old/new/g` | Replace all occurrences in the current line. |
| `:s/old/new/gc` | Replace all occurrences and ask for confirmation. |

---

## 🎨 Visual Mode

| Command | Description |
|---------|-------------|
| `v` | Start visual mode (character-wise selection). |
| `V` | Start visual mode (line-wise selection). |
| `Ctrl + v` | Start visual block mode (columnar selection). |
| `y` | Yank (copy) the selected text. |
| `d` | Delete the selected text. |
| `>` | Indent the selected text. |
| `<` | Un-indent the selected text. |
| `=` | Auto-indent the selected text. |

---

## 📋 Clipboard & Registers

| Command | Description |
|---------|-------------|
| `"+y` | Yank (copy) to the system clipboard. |
| `"+p` | Paste from the system clipboard. |
| `:registers` | Show all available registers. |
| `"xy` | Yank to register `x`. |
| `"xp` | Paste from register `x`. |

---

## ⚙️ Configuration & Customization

| Command | Description |
|---------|-------------|
| `:set number` | Show line numbers. |
| `:set nonumber` | Hide line numbers. |
| `:set autoindent` | Enable auto-indentation. |
| `:set tabstop=4` | Set tab width to 4 spaces. |
| `:set expandtab` | Use spaces instead of tabs. |
| `:set relativenumber` | Show relative line numbers. |
| `:syntax on` | Enable syntax highlighting. |
| `:set hlsearch` | Highlight search results. |
| `:set ignorecase` | Ignore case in searches. |
| `:set smartcase` | Enable case sensitivity in search if uppercase letters are used. |

---

## 🧰 Advanced Features

| Command | Description |
|---------|-------------|
| `:e <file>` | Edit a different file. |
| `:w <file>` | Save the current file as `<file>`. |
| `:vsp <file>` | Open file in a vertical split window. |
| `:sp <file>` | Open file in a horizontal split window. |
| `Ctrl + w h/j/k/l` | Navigate between split windows. |
| `:tabnew` | Open a new tab. |
| `:tabn` | Go to the next tab. |
| `:tabp` | Go to the previous tab. |
| `:m` | Move current line or selection. |

---

## 📅 Exiting Vim

| Command | Description |
|---------|-------------|
| `:w` | Save file. |
| `:wq` | Save and quit. |
| `:x` | Save and quit (same as `:wq`). |
| `:q!` | Quit without saving. |
| `ZZ` | Save and quit (shortcut). |

---
