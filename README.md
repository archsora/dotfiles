Dotfiles Configuration Guide
System Requirements
Essential Software
    Operating System: Arch Linux (or Arch-based distribution)
    Display Server: Wayland
    Window Manager: Hyprland
    Package Manager: Yay (AUR helper)

Terminal & Shell
    Terminal: Kitty
    Shell: Zsh with Oh My Zsh
    Zsh Plugins:
        git
        sudo (optional)
        zsh-autosuggestions
        zsh-syntax-highlighting
        zsh-history-substring-search
        any other preferred plugins

Core Applications
    Version Control: Git
    Status Bar: Waybar
    Application Launcher: Rofi
    Logout Menu: Wlogout
    Text Editor: Neovim (with LazyVim configuration)

Development Tools
    Neovim Prerequisites:
        Neovim (built with Lua support)
        C compiler for nvim-treesitter
        LazyVim plugin manager
    Git Tools:
        lazygit (optional but recommended)
        ghq (Git repository organizer)

Terminal Enhancements
    File Lister: Eza (modern ls replacement)
    File Manager: Ranger
    System Monitor: btop
    Audio Visualizer: cava
    System Info: fastfetch

Visual Requirements
    Font: Nerd Font (optional but recommended for icons)
    Terminal Support:
        True color support
        Undercurl support


### 1. Configuration Files
```
~/.config/
├── hypr/           # Hyprland configuration
├── kitty/          # Terminal configuration
├── waybar/         # Status bar configuration
├── rofi/           # Application launcher
├── wlogout/        # Logout menu
└── nvim/           # Neovim (LazyVim) configuration
```

### 2. Shell Configurations
```
~/
├── .zshrc          # Zsh configuration
├── .zsh_plugins    # Zsh plugin management
└── .oh-my-zsh/     # Oh My Zsh framework
```

### 3. Utility Configurations
```
~/
├── .gitconfig      # Git configuration
├── .tmux.conf      # Tmux configuration (if used)
└── local/bin/      # Custom scripts and tools
```

nstallation Checklist
Phase 1: Base System
    Install Arch Linux with base-devel
    Install and configure Hyprland
    Install yay (AUR helper)

Phase 2: Core Applications
    Install Git
    Install Kitty terminal
    Install Zsh and Oh My Zsh
    Install Neovim (with Lua support)

Phase 3: Desktop Environment
    Install and configure Waybar
    Install and configure Rofi
    Install and configure Wlogout

Phase 4: Development Setup
    Install C compiler (gcc or clang)
    Set up LazyVim for Neovim
    Install nvim-treesitter dependencies
    Install lazygit and ghq

Phase 5: Terminal Utilities
    Install Eza
    Install Ranger
    Install btop
    Install cava
    Install fastfetch

Phase 6: Fonts & Themes
    Install Nerd Font (optional)
    Apply desired color schemes
    Configure terminal themes

Post-Installation Verification
    Terminal Check:
        Verify true color support
        Check undercurl rendering
        Test Nerd Font icons
        
  Neovim Check:
        Confirm LazyVim installation
        Verify treesitter parsing
        Test plugin functionality

  Shell Check:
        Verify Zsh is default shell
        Test Oh My Zsh plugins
        Confirm Eza replaces ls
    Git Check:
        Verify ghq repository organization
        Test lazygit functionality
    Hyprland Check:
        Test window management
        Verify Waybar functionality
        Confirm Rofi launches applications

Notes
    Ensure all terminal applications support true color and undercurl
    Keep backup of existing configurations before overwriting
    Test each component individually before full integration
    Consider using a configuration management tool (like GNU Stow) for dotfile organization

Troubleshooting
    If Neovim treesitter fails: Install a C compiler and restart Neovim
    If icons don't display: Install a Nerd Font and configure terminal
    If colors appear wrong: Verify terminal true color support
    If plugins don't load: Check internet connection and plugin manager logs

This configuration provides a complete development environment with modern tools and aesthetic desktop setup.
