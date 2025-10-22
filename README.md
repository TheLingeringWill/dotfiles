# Development Environment Setup

Modern AI-boosted terminal-based development environment: Neovim (LazyVim) + Tmux + Alacritty with Catppuccin Mocha theme and Claude Code integration.

## Prerequisites

- **Neovim** (text editor)
- **Tmux** (terminal multiplexer)
- **Alacritty** (terminal emulator)
- **Git**
- **TerminalVector font** (or any Nerd Font for icons)
- **Claude Code** (AI coding assistant built into Neovim)

## Setup

1. Backup your existing configs if they exist:

   ```bash
   mv ~/.config/nvim ~/.config/nvim.backup
   mv ~/.config/alacritty ~/.config/alacritty.backup
   mv ~/.config/tmux ~/.config/tmux.backup
   ```

2. Clone this repository:

   ```bash
   git clone https://github.com/TheLingeringWill/dotfiles.git ~/.config-temp
   cp -r ~/.config-temp/{nvim,alacritty,tmux} ~/.config/
   rm -rf ~/.config-temp
   ```

3. Launch Neovim - plugins will install automatically:

   ```bash
   nvim
   ```

4. Start Tmux and enjoy:

   ```bash
   tmux
   ```

